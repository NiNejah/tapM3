veet a javascript build tool that
simplifies the way we build and develop
front-end web applications at its core
it does two things : 
one serve your code locally during development and 
two bundle your javascript css and other

assets together for production there are
many other tools out there that do the
same thing like webpack so what makes
vee different well it was created by
evan yu who also created vue.js as a way
to both simplify and speed up the build
process not long ago web developers had
no native way to combine javascript
files together in a modular way this led
to tools like webpack and rollup that
concatenate multiple files together into
a single bundle for the browser the
problem is that this process becomes
increasingly slow as the app adds more
code and dependencies in 2015 ecmascript
modules were introduced and by 2020 had
wide browser support allowing developers
to import and export code from different
files in the browser veed leverages
native es modules in the browser to load
your code instantly no matter how large
the app is it also supports hot module
replacement for an extremely fast
feedback loop during development when
building for production it uses roll up
under the hood so you don't have to
worry about configuring it it's an
opinionated tool that provides
conventions that work out of the box for
the majority of developers to get
started run npm netweat from the command
line and choose a starter project with
your favorite front-end framework you'll
notice the project comes with a v-config
file it has a plug-in ecosystem that can
extend it with additional features and
you can also manually override the
roll-up defaults when necessary and
there are some really cool plugins out
there like vtssr that can do server-side
rendering like next.js now to serve the
application locally run npm run dev even
if i install a bunch of big dependencies
like low dash and moment the time to run
the dev server does not change now if
you open the network tab in the browser
dev tools you'll notice that instead of
importing a single javascript bundle
file it's importing our actual source
code like a raw tsx file in this case it
also makes typescript about 20 to 30
times faster because it skips type
checking and uses es build to transpile
your code now as you're developing your
app you might change the state of it in
the ui then realize that some of the
code needs to change when you modify the
source code the changes will be
reflected instantly without losing the
state of the application that's what we
call hot module replacement now run npm
build to build the app for production
this will generate a javascript bundle
with rollup with a bunch of automatic
optimizations like automatic code
splitting for any dynamic imports and
css this has been beat in 100 seconds if
you want to see more short videos like
this hit the like button and subscribe
thanks for watching and i will see you
in the next one