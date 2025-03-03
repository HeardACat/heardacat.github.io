## Bookmarks and Stuff

Here are things that I didn't invent, but I find myself constantly referring back to.

---

### Architecture Decision Record

My go-to template is the [Alexandrian Pattern]([https://github.com/jamesmh/architecture_decision_record/blob/master/adr_template_for_alexandrian_pattern.md](https://github.com/joelparkerhenderson/architecture-decision-record/tree/main/locales/en/templates/decision-record-template-for-alexandrian-pattern)), which is based on [Design Pattern from Christopher Alexander](https://en.wikipedia.org/wiki/Design_pattern)

#### Introduction

* Prologue (Summary)
* Discussion (Context)
* Solution (Decision)
* Consequences (Results)

#### Specifics

* Prologue (Summary)
  * Statement to summarize:
    * In the context of (use case)<br>
      facing (concern)<br>
      we decided for (option)<br>
      to achieve (quality)<br>
      accepting (downside).
* Discussion (Context)
  * Explains the forces at play (technical, political, social, project).
  * This is the story explaining the problem we are looking to resolve.
* Solution
  * Explains how the decision will solve the problem.
* Consequences
  * Explains the results of the decision over the long term.
  * Did it work, not work, was changed, upgraded, etc.
 
---

### HTML Template

[Pico](https://picocss.com/) has proven to me to be a good enough HTML template with sensible defaults. It can be classless if you want it to be, or you can have some extras on top. 

It provides you with a good starter template.

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="color-scheme" content="light dark">
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/@picocss/pico@2/css/pico.min.css"
    >
    <title>Hello world!</title>
  </head>
  <body>
    <main class="container">
      <h1>Hello world!</h1>
    </main>
  </body>
</html>
```

Color scheme overrides can be done just by adding an attribute to the html tag, e.g. `<html data-theme="light">`.

