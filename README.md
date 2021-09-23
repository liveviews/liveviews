# LiveViews

This is a list of libraries for creating web applications that handle user interaction with the [DOM](https://en.wikipedia.org/wiki/Document\_Object\_Model) on the server.  These libraries take a different approach from older server-driven browser UIs that simulated a desktop GUI toolkit.  They do not lock the developer into working with predefined components; most operate at the level of HTML (DOM) rather than GUI widgets.

The list strives to be complete rather than [awesome](https://github.com/sindresorhus/awesome).  You may see libraries that are not maintained or ready for production.

## List

### C#

* [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/client).  "Build client web apps with C#."

### Clojure

* [liveview\-clj](https://github.com/prepor/liveview-clj). "Server-side HTML rendering with reactive updates. Massively inspired by Elixir's LiveView."
* [Ripley](https://github.com/tatut/ripley). "Ripley is a fast server-side rendered web UI toolkit with live components."

### Common Lisp

* [CLOG](https://github.com/rabbibotton/clog).  "The Common Lisp Omnificent GUI, CLOG for short, uses web technology to produce graphical user interfaces for applications locally or remotely."
* [ISSR](https://github.com/interactive-ssr/client/blob/master/main.org/).  ISSR allows you to make interactive web pages without client-side scripting.  "No knowledge about Javascript or DOM is necessary."  [To-do app tutorial](http://cjackson.tk/todo-tutorial).

### Crystal

* [jgaskins/live\_view](https://github.com/jgaskins/live\_view).  "A Crystal abstract class for building server-rendered HTML components with client-side interactivity."

### Elixir

* [Drab](https://github.com/grych/drab).  "Remote controlled frontend framework for Phoenix."
* [Phoenix LiveView](https://github.com/phoenixframework/phoenix\_live\_view).  "Phoenix LiveView enables rich, real-time user experiences with server-rendered HTML."

### Haskell

* [Replica](https://github.com/pkamenarsky/replica).  "A remote virtual DOM library for Haskell."

### Java

* [Vaadin](https://vaadin.com). "Full stack framework for building web apps in Java."

### JavaScript/TypeScript

* [Caldera](https://github.com/calderajs/caldera-react).  JavaScript (Node.js).  "Phoenix LiveView for Node and React ."
* [Purview](https://github.com/karthikv/purview).  JavaScript (Node.js).  "A server-side component framework. What if your React components ran on the server-side?"
* [TS-LiveView](https://github.com/beenotung/ts-liveview). TypeScript (Node.js). "Just like Phoenix LiveView but in TypeScript!"
* [Blitz](https://github.com/blitz-js/blitz). TypeScript (Node.js). "'Zero-API' Data Layer — Built on Next.js — Inspired by Ruby on Rails"

### Kotlin

* [Kweb](http://docs.kweb.io/). "A new way to create beautiful, efficient, and scalable websites in Kotlin"

### PHP

* [Livewire](https://github.com/livewire/livewire).  "A full-stack framework for Laravel that takes the pain out of building dynamic UIs."  Relies solely on Ajax requests.

### Python

* [Flexx](https://github.com/flexxui/flexx).  (Widget-centric.)  "Write desktop and web apps in pure Python."
* [IDOM](https://github.com/idom-team/idom).  "Create highly interactive web pages purely in Python."
* [Reactor](https://github.com/edelvalle/reactor).  "Phoenix LiveView but for Django."
* [REMI](https://github.com/dddomodossola/remi).  (Widget-centric.)  "Remi is a GUI library for Python applications that gets rendered in web browsers."
* [Sockpuppet](https://github.com/jonathan-s/django-sockpuppet).  "Build reactive applications with the django tooling you already know and love."
* [WDOM](https://github.com/miyakogi/wdom).  "WDOM is a Python GUI library for browser-based desktop applications."

### Ruby

* [Fie](https://github.com/raen79/fie).  "Fie is a Rails-centric frontend framework running over a permanent WebSocket connection."
* [RenderSync](https://github.com/chrismccord/render\_sync).  "Real-time partials with Rails."
* [StimulusReflex](https://github.com/hopsoft/stimulus\_reflex).  "Build reactive applications with the Rails tooling you already know and love."

### Scala

* [Korolev](https://github.com/fomkin/korolev).  "Single Page Applications running on the server side."

### V

* [Simple V LiveView Clone](https://github.com/atomkirk/v-playground).  A simple implementation of LiveView in V.  A demo, not a library.

## Contributing

You contributions are welcome.  Please be sure the library you are submitting meets the definition of "live view" above.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, D. Bohdan has waived all copyright and related or neighboring rights to this work.  If you contribute, you agree to release your contribution under the same license.
