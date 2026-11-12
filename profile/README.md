<div align="center">

### One environment, every platform, built from the first byte up.

One language (**Envo**), one toolchain (`envo`) and one standard platform (`envo.*`)
for systems code, scripts, apps, websites, graphics, AI, crypto and networking.
No third-party dependencies, and a compiler bootstrapped from assembly.

<a href="https://discord.gg/Ev9ZeRVrX5"><img src="assets/button-discord.svg" alt="Join the Discord" width="144" height="44"></a> <a href="https://github.com/orgs/envoscale/projects/3"><img src="assets/button-roadmap.svg" alt="View the roadmap" width="144" height="44"></a>

</div>

<br>

<p align="center">
  <img src="assets/terminal.svg" alt="envoc0 compiling Hello World into a 1,277-byte Linux executable" width="840">
</p>

## Built from the first byte

Stage 0 is a compiler written in x86-64 assembly. It writes Windows and Linux executables
directly, with no C runtime, linker or libraries. Each later compiler is written in more
of Envo and built by the one before it, until the compiler builds itself.

<p align="center">
  <img src="assets/bootstrap.svg" alt="The bootstrap ladder: seed, Stage 0, Stage 1, Stage 2 and the fixed point" width="840">
</p>

## Stage 1

`envoc1` is the first compiler written in Envo. It goes from source to tokens, syntax tree,
EIR (a typed SSA form), x86-64 and a PE or ELF file. Every test program is compiled by
both `envoc0` and `envoc1`, and the results have to match.

<p align="center">
  <img src="assets/pipeline.svg" alt="The envoc1 pipeline: source, tokens, syntax tree, EIR, x86-64, executable" width="840">
</p>

## Hello World, everywhere

Every domain gets a Hello World of one to three lines, and CI fails if one breaks or
gets longer. Only the console one runs today; the rest arrive with their milestones.

<p align="center">
  <img src="assets/gallery.svg" alt="Hello World Gallery: console, CLI, window, website, HTTP API, terminal UI, 3D, 2D, crypto, AI, systems" width="840">
</p>

## Progress

<p align="center">
  <img src="assets/roadmap.svg" alt="Roadmap: M0 to M2 done, M3 in progress" width="840">
</p>

- **Done:** M0 specs and skeleton, M1 Stage 0 in assembly, M2 Stage 1 in Envo
- **Now:** M3, the compiler that compiles itself
- **Later:** standard library, `envo` CLI, UI and web, more platforms, 3D, AI

Follow along on the [roadmap](https://github.com/orgs/envoscale/projects/3) or
[Discord](https://discord.gg/Ev9ZeRVrX5).

## License

Free for personal, educational and other noncommercial use under the
[PolyForm Noncommercial License 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0/).
Commercial use needs a commercial license.
