---
layout: page
title: Sebuah JavaScript library untuk membangun user interfaces
id: home
---

<section class="light home-section">
  <div class="marketing-row">
    <div class="marketing-col">
      <h3>Deklarasi</h3>
      <p>React untuk membuat UI interaktif tanpa menyusahkan. Desain tampilan sederhana untuk setiap keadaan dalam aplikasi Anda, dan React akan memperbarui secara efisien dan hanya merender komponen yang tepat ketika data anda berubah.</p>
      <p>Deklarasi views membuat kode anda lebi predictable and lebih mudah untuk didebug.</p>
    </div>
    <div class="marketing-col">
      <h3>Basis Komponene</h3>
      <p>Bangun rumusan komponen untuk mengelola keadaannya, kemudian ubah menjadi UIS yang kompleks.</p>
      <p>Sejak komponen logika ditulis dalam JavaScript pengganti dari template, anda dapat dengan mudah mengumpan data yang kaya melalui aplikasi anda dan  menjaga keadaan DOM.</p>
    </div>
    <div class="marketing-col">
      <h3>Belajar sekali, Tulis segalanya</h3>
      <p>We don't make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code.</p>
      <p>React can also render on the server using Node and power mobile apps using <a href="https://facebook.github.io/react-native/">React Native</a>.</p>
    </div>
  </div>
</section>
<hr class="home-divider" />
<section class="home-section">
  <div id="examples">
    <div class="example">
      <h3>A Simple Component</h3>
      <p>
        React components implement a `render()` method that takes input data and
        returns what to display. This example uses an XML-like syntax called
        JSX. Input data that is passed into the component can be accessed by
        `render()` via `this.props`.
      </p>
      <p>
        <strong>JSX is optional and not required to use React.</strong> Try
        clicking on "Compiled JS" to see the raw JavaScript code produced by
        the JSX compiler.
      </p>
      <div id="helloExample"></div>
    </div>
    <div class="example">
      <h3>A Stateful Component</h3>
      <p>
        In addition to taking input data (accessed via `this.props`), a
        component can maintain internal state data (accessed via `this.state`).
        When a component's state data changes, the rendered markup will be
        updated by re-invoking `render()`.
      </p>
      <div id="timerExample"></div>
    </div>
    <div class="example">
      <h3>An Application</h3>
      <p>
        Using `props` and `state`, we can put together a small Todo application.
        This example uses `state` to track the current list of items as well as
        the text that the user has entered. Although event handlers appear to be
        rendered inline, they will be collected and implemented using event
        delegation.
      </p>
      <div id="todoExample"></div>
    </div>
    <div class="example">
      <h3>A Component Using External Plugins</h3>
      <p>
        React is flexible and provides hooks that allow you to interface with
        other libraries and frameworks. This example uses **remarkable**, an
        external Markdown library, to convert the textarea's value in real time.
      </p>
      <div id="markdownExample"></div>
    </div>
  </div>
  <script src="/react/js/remarkable.min.js"></script>
  <script src="/react/js/examples/hello.js"></script>
  <script src="/react/js/examples/timer.js"></script>
  <script src="/react/js/examples/todo.js"></script>
  <script src="/react/js/examples/markdown.js"></script>
</section>
<hr class="home-divider" />
<section class="home-bottom-section">
  <div class="buttons-unit">
    <a href="docs/getting-started.html" class="button">Get Started</a>
    <a href="downloads.html" class="button">Download React v{{site.react_version}}</a>
  </div>
</section>
