
[![parinfer-org-logo-256x256][logo-img]][logo-repo]

[logo-img]: https://user-images.githubusercontent.com/71587/191460276-ca711cbb-7d71-41a6-949b-8201ff32e896.png
[logo-repo]: https://github.com/parinfer/parinfer-logo

# Parinfer

### [Let’s simplify the way we write Lisp](https://shaunlebron.github.io/parinfer/)

Parinfer is a new kind of editor plugin that improves the experience of writing code in Lisp.  Through research it was discovered that by enforcing a formal relationship between parentheses and indentation, we can allow more kinds of structural editing operations without hotkeys.

(See the link above for details in the original research paper.)

## 👋 Welcome to the Parinfer org!

We exist to facilitate the continued development of Parinfer as a real practitioner’s tool— as much as possible for modern editors today, and also to influence better support in editors tomorrow.

### Status

<table>
<tr>
<td>🔬</td>
<td><b>As a research project</b>, Parinfer was completed and archived in 2019 after the design of a “Smart Mode” was completed.</td>
</tr>
</table>

<table>
<tr>
<td>⚙️</td>
<td><b>As a community tool for real programmers</b>, Parinfer is still at various stages of development across editors.  And there are still more fixes and tooling needed to make Parinfer work more broadly across different languages and team conventions.
</table>

Development on the following roadmap started in September 2022.

### Roadmap

- [x] ~~[Parstager]: undo parinfer formatting on unchanged top-level forms before staging in git~~
- [ ] Fixes for [non-clojure dialects](https://github.com/parinfer/parinfer.js/issues/209)
- [ ] Canonical exe to share between plugins (in c)
- [ ] Clarify and facilitate editor support (e.g. vscode)
- [ ] Simplified landing page
- [ ] Create a visual model for describing Parinfer’s operations (e.g. based on the “pills” in the logo)
- [ ] Include historical visual models created for [Clojure Conj 2017](https://youtu.be/K0Tsa3smr1w?t=144)

[Parstager]:https://github.com/parinfer/parstager
