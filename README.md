<!-- markdownlint-disable MD033 MD041 -->

<img
  align="right"
  alt="Logo of L90S"
  height="261"
  src="https://kura.pro/l90s/images/logos/l90s.webp"
  width="261"
  />

<!-- markdownlint-enable MD033 MD041 -->

# l90s.com - Official Website 🌏

Welcome to the repository for [l90s.com][00], established to address the unique
financial needs of new entrepreneurs and founders, offering a cost-effective
solution.

## Quick Start Guide

Setting up and running the website locally is easy and quick with the
[Shokunin Static Site Generator (SSG)][00].

### Prerequisites

Ensure you have the **Rust toolchain** installed. If not, follow the guide on
the [Rust website][01] to set it up.

### Installation & Usage

1. Install Shokunin SSG:

```shell
cargo install ssg
```

2. Clone the repository

```shell
git clone https://github.com/sebastienrousseau/l90s.github.io.git
```

3. Change into the repository directory:

```shell
cd l90s.github.io
```

4. Generate the static site for l90s.com:

```shell
ssg -n=docs -c=_posts -t=_layouts -o=output -s=public
```


[00]: https://l90s.com "L90S Official Website"
[01]: https://www.rust-lang.org/learn/get-started "Rust Getting started guide"
