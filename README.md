


# Tool Mappings

| Tool           | Lean           | Rust            | Haskell               | OCaML          | Coq                 | Isabelle/HOL       |
| :---           | :---           | :---            | :---                  | :---           | :---                | :---               |
| Installer      | [elan]         | [rustup]        | [ghcup]               | [opam]         | [Coq Platform]      |                    |
| Build          | [lake]         | [cargo]         | [cabal], [stack]      | [dune]         | [dune]?             |                    |
| Execution      | [lean]         | [rustc]         | [ghc]                 | [OCaML]        | [Coq]               | [Isabelle]         |
| Package Index  | [reservoir]    | [crates.io]     | [hackage], [stackage] | [ocaml index]  | [Coq Package Index] |                    |
| Doc Generation | [doc-gen]      | [rustdoc]       | [haddock]             | [ocamldoc]     | [coqdoc]            |                    |
| Doc Index      |                | [docs.rs]       | [hackage]             | [ocaml index]  |                     |                    |
| IDE Plugins    | [vscode-lean4] | [rust-analyzer] | [haskell lsp]         | [ocaml vscode] | [VSCoq]             | [Isabelle/VSCode]  |
| Standard Lib   |                |                 | [Haskell base]        |                | [coq stdlib]        | [library][Isabelle library] |

[elan]: https://github.com/leanprover/elan
[lake]: https://github.com/leanprover/lake
[lean]: https://lean-lang.org/
[reservoir]: https://reservoir.lean-lang.org
[doc-gen]: https://github.com/leanprover-community/doc-gen
[vscode-lean4]: https://github.com/leanprover/vscode-lean4

[rustup]: https://rustup.rs/
[cargo]: https://github.com/rust-lang/cargo
[rustc]: https://github.com/rust-lang/rust
[crates.io]: https://crates.io/
[rustdoc]: https://doc.rust-lang.org/rustdoc
[docs.rs]: https://docs.rs/
[rust-analyzer]: https://code.visualstudio.com/docs/languages/rust

[ghcup]: https://www.haskell.org/ghcup/
[cabal]: https://www.haskell.org/cabal/
[stack]: https://haskellstack.org
[ghc]:   https://www.haskell.org/ghc
[hackage]: https://hackage.haskell.org/
[stackage]: https://www.stackage.org/
[haddock]: http://www.haskell.org/haddock/
[haskell lsp]: https://github.com/haskell/lsp
[Haskell base]: https://hackage.haskell.org/package/base

[opam]: https://opam.ocaml.org/
[dune]: https://dune.build/
[ocaml]: https://ocaml.org/
[ocaml index]: https://ocaml.org/packages
[ocamldoc]: https://v2.ocaml.org/manual/ocamldoc.html
[ocaml vscode]: https://github.com/ocamllabs/vscode-ocaml-platform

[Coq Platform]: https://github.com/coq/platform
[Coq]: https://coq.inria.fr/
[Coq Package Index]: https://coq.inria.fr/packages.html
[coqdoc]: https://coq.inria.fr/refman/using/tools/coqdoc.html
[VSCoq]: https://github.com/coq-community/vscoq
[coq stdlib]: https://coq.inria.fr/doc/V8.17.1/stdlib/

[Isabelle]: https://isabelle.in.tum.de/
[Isabelle/VSCode]: https://github.com/seL4/isabelle/tree/master/src/Tools/VSCode
[Isabelle library]: https://isabelle.in.tum.de/dist/library/

# Pragmas (TODO)

`@[inline]`
