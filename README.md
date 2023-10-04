# Lean Cheatsheet

Various links relevant to working on Lean

## Tool Mappings

| Tool           | Lean                 | Rust            | Haskell               | OCaML          | Coq                                   | Isabelle/HOL       |
| :---           | :---                 | :---            | :---                  | :---           | :---                                  | :---               |
| Installer      | [elan]               | [rustup]        | [ghcup]               | [opam]         | [Coq Platform]                        |                    |
| Build          | [lake]               | [cargo]         | [cabal], [stack]      | [dune]         | [coq_makefile], [dune] (experimental) |                    |
| Execution      | [lean]               | [rustc]         | [ghc]                 | [OCaML]        | [Coq]                                 | [Isabelle]         |
| Package Index  | [reservoir]          | [crates.io]     | [hackage], [stackage] | [ocaml index]  | [Coq Package Index]                   |                    |
| Doc Generation | [doc-gen], [lean2md] | [rustdoc]       | [haddock]             | [ocamldoc]     | [coqdoc]                              |                    |
| Doc Index      |                      | [docs.rs]       | [hackage]             | [ocaml index]  |                                       |                    |
| IDE Plugins    | [vscode-lean4]       | [rust-analyzer] | [haskell lsp]         | [ocaml vscode] | [VSCoq], [coq-lsp]                    | [Isabelle/VSCode]  |
| Standard Lib   | [std4]               |                 | [Haskell base]        |                | [coq stdlib], [stdpp]                 | [library][Isabelle library] |

[elan]: https://github.com/leanprover/elan
[lake]: https://github.com/leanprover/lake
[lean]: https://lean-lang.org/
[reservoir]: https://reservoir.lean-lang.org
[doc-gen]: https://github.com/leanprover-community/doc-gen
[lean2md]: https://github.com/arthurpaulino/lean2md
[vscode-lean4]: https://github.com/leanprover/vscode-lean4
[std4]: https://github.com/leanprover/std4

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
[coq_makefile]: https://coq.inria.fr/refman/practical-tools/utilities.html#building-a-project-with-coqproject-overview
[coq-lsp]: https://github.com/ejgallego/coq-lsp
[stdpp]: https://gitlab.mpi-sws.org/iris/stdpp

[Isabelle]: https://isabelle.in.tum.de/
[Isabelle/VSCode]: https://github.com/seL4/isabelle/tree/master/src/Tools/VSCode
[Isabelle library]: https://isabelle.in.tum.de/dist/library/

## Documentation

* [Functional Programming in Lean]
* [Lean Metaprogramming] 

[Functional Programming in Lean]: https://lean-lang.org/functional_programming_in_lean
[Lean Metaprogramming]: https://github.com/leanprover-community/lean4-metaprogramming-book

## Major Lean Formalizations

* [Liquid Tensor Project]
* [Mathlib]

[Mathlib]: https://reservoir.lean-lang.org/packages/leanprover--community-mathlib4
[Liquid Tensor Project]: https://github.com/leanprover-community/liquid

## Coding Style

* [Library Style Guidelines]

[Library Style Guidelines]: https://leanprover-community.github.io/contribute/style.html

## DevOps Infrastructure

* [GitHub Actions] based continuous integration for core Lean.
* [Lean Speedcenter] shows performance of core lean over time.

[Github Actions]: https://docs.github.com/en/actions
[Lean speedcenter]: http://speedcenter.informatik.kit.edu/lean/

## Other Lean Tools

[Duper] is a work-in-progress first-order prover

[Lean Blueprint] is a [PlasTeX] plugin for creating blueprints for Lean projects.

[Duper]: https://github.com/leanprover-community/duper
[Lean Blueprint]: https://github.com/PatrickMassot/leanblueprint
[PlasTeX]: https://github.com/plastex/plastex/