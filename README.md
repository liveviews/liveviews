# LiveViews

This is a list of libraries for creating dynamic web applications that handle user interaction with the [DOM](https://en.wikipedia.org/wiki/Document_Object_Model) on the server.
These libraries are different from component-based web UI libraries.
They operate at the level of HTML rather than GUI widgets,
which means the developer gets a blank canvas (with its advantages and disadvantages), isn't tied to a particular set of components, and can directly use their knowledge of HTML.

The list strives to be complete rather than [awesome](https://github.com/sindresorhus/awesome).
You may see libraries that are not maintained, not ready for production, or both.

## List

### C#

- [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/client).
  "Build client web apps with C#."

### Clojure

- [liveview-clj](https://github.com/prepor/liveview-clj).
  "Server-side HTML rendering with reactive updates. Massively inspired by Elixir's LiveView."
- [Ripley](https://github.com/tatut/ripley).
  "Ripley is a fast server-side rendered web UI toolkit with live components."

### Common Lisp

- [CLOG](https://github.com/rabbibotton/clog).
  "The Common Lisp Omnificent GUI, CLOG for short, uses web technology to produce graphical user interfaces for applications locally or remotely."
- [ISSR](https://github.com/interactive-ssr/client/blob/master/main.org/).
  ISSR allows you to make interactive web pages without client-side scripting. "No knowledge about Javascript or DOM is necessary." [To-do app tutorial](http://cjackson.tk/todo-tutorial).
- [reblocks](https://github.com/40ants/reblocks).
  A fork of Weblocks Common Lisp web framework
### Crystal

- [jgaskins/live_view](https://github.com/jgaskins/live_view).
  "A Crystal abstract class for building server-rendered HTML components with client-side interactivity."

### Elixir

- [Drab](https://github.com/grych/drab).
  "Remote controlled frontend framework for Phoenix."
- [Phoenix LiveView](https://github.com/phoenixframework/phoenix\_live\_view).
  "Phoenix LiveView enables rich, real-time user experiences with server-rendered HTML."

### Go (golang)

- [live](https://github.com/jfyne/live).
  Real-time user experiences with server-rendered HTML in Go. Inspired by and borrowing from Phoenix LiveViews.

### Haskell

- [Replica](https://github.com/pkamenarsky/replica).
  "A remote virtual DOM library for Haskell."

### Java

- [Vaadin](https://vaadin.com).
  "Full stack framework for building web apps in Java."

### JavaScript/TypeScript

- [Caldera](https://github.com/calderajs/caldera-react).
  JavaScript (Node.js).
  "Phoenix LiveView for Node and React ."
- [LiveViewJS](https://github.com/floodfx/liveviewjs).
  TypesScript (Node.js).
  "A backend implementation of Phoenix LiveView in Typescript"
- [Nanoweb](https://nanoweb.js.org/).
  TypeScript (Node.js).
  "Minimal library for building server-centric multi page web applications that behave like SPAs"
- [Purview](https://github.com/karthikv/purview).
  JavaScript (Node.js).
  "A server-side component framework. What if your React components ran on the server-side?"
- [ts-liveview](https://github.com/beenotung/ts-liveview).
  TypeScript (Node.js).
  "Build hybrid SSG and SSR realtime SPA/MPA with Typescript"

### Kotlin

- [Kweb](http://docs.kweb.io/).
  "A new way to create beautiful, efficient, and scalable websites in Kotlin"

### PHP

- [Livewire](https://github.com/livewire/livewire).
  "A full-stack framework for Laravel that takes the pain out of building dynamic UIs." Relies solely on Ajax requests.

### Python

- [Flask-Meld](https://www.flask-meld.dev/).
  "Flask-Meld is a library to provide server rendered templates over websockets for Flask applications to build reactive components without Javascript"
- [Django Hypergen](https://github.com/runekaagaard/django-hypergen/).
  "Take a break from javascript. Write server-rendered reactive HTML liveviews for Django in pure python. 💫"
- [Django LiveView](https://github.com/Django-LiveView/liveview).
  "Django template for creating a complete HTML over the Wire site or LiveView."
- [Django Unicorn](https://www.django-unicorn.com).
  "Django Unicorn is a library that enables real-time, reactive components in Django applications using simple Python and HTML, reducing the need for extensive JavaScript."
- [dominator](https://github.com/FFY00/dominator).
  "Control the DOM from Python (PoC!)"
- [jyserver](https://github.com/ftrias/jyserver).
  "Jyserver Web Framework with Pythonic Javascript Syntax"
- [liveview](https://github.com/abravalheri/liveview).
  "Real time browser <> ASGI communication / re-rendering for Python (inspired by Phoenix Live View)"
- [portkey](https://github.com/red8012/portkey).
  "A Python framework for interacting with in-browser DOM via websockets"
- [pyview](https://github.com/ogrodnek/pyview).
  "A Python implementation of Phoenix LiveView"
- [Reactor](https://github.com/edelvalle/reactor).
  "Phoenix LiveView but for Django."
- [ReactPy](https://github.com/reactive-python/reactpy).
  "It's React, but in Python"
- [Skink](https://github.com/oksome/Skink).
  "Control the DOM from Python using Websockets"
- [Sockpuppet](https://github.com/jonathan-s/django-sockpuppet).
  "Build reactive applications with the django tooling you already know and love."
- [starlette_live](https://github.com/alex-oleshkevich/starlette_live).
  "Live view for Starlette"
- [WDOM](https://github.com/miyakogi/wdom). "WDOM is a Python GUI library for browser-based desktop applications."

### Ruby

- [Fie](https://github.com/raen79/fie).
  "Fie is a Rails-centric frontend framework running over a permanent WebSocket connection."
- [Mayu Live](https://github.com/mayu-live/framework).
  "Mayu is a live-streaming server-side component-based VDOM rendering framework written in Ruby."
- [RenderSync](https://github.com/chrismccord/render_sync).
  "Real-time partials with Rails."
- [StimulusReflex](https://github.com/hopsoft/stimulus_reflex).
  "Build reactive applications with the Rails tooling you already know and love."

### Rust

- [axum-live-view](https://github.com/davidpdrsn/axum-live-view).
  "axum-live-view allows you to build rich, real-time experiences with server-rendered HTML. This is done entirely in Rust - no JavaScript or WASM needed."
- [Dioxus](https://github.com/dioxuslabs/dioxus).
  "Dioxus can be used to deliver webapps, desktop apps, static sites, liveview apps, mobile apps (WIP), and more."

### Scala

- [Korolev](https://github.com/fomkin/korolev).
  "Single Page Applications running on the server side."

### V

- [Simple V LiveView Clone](https://github.com/atomkirk/v-playground). A simple implementation of LiveView in V. A demo, not a library.

### Server language-agnostic

- [Turbo](https://turbo.hotwired.dev/).
  "The speed of a single-page web application without having to write any JavaScript."

## Contributing

You contributions are welcome.
Please be sure the library you are submitting meets the definition of "live view" above.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, D. Bohdan has waived all copyright and related or neighboring rights to this work.
If you contribute, you agree to release your contribution under the same license.
