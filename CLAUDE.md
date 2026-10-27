Read [AGENTS.md](AGENTS.md) first: it is the guide for every agent and contributor working in this repository.

New workspace crates must include `[lints] workspace = true` in `Cargo.toml` to inherit
`[workspace.lints]`; production crate roots must begin with the required crate-level lint attribute.
