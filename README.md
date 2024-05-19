# LeanIMT Paper

This repository contains the LeanIMT Paper.

## Related work

- LeanIMT document: https://hackmd.io/@vplasencia/S1whLBN16

- LeanIMT benchmarks on browser and Node.js: https://github.com/vplasencia/imt-benchmarks

## Code

- LeanIMT TypeScript implementation: https://github.com/privacy-scaling-explorations/zk-kit/tree/main/packages/lean-imt.

- LeanIMT Solidity implementation: https://github.com/privacy-scaling-explorations/zk-kit.solidity/tree/main/packages/lean-imt.

## Install Latex to work with VSCode on Mac

1. Install [Miktex](https://miktex.org/).

2. Install [LaTeX Workshop VSCode extension](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop).

3. Add the path by running:

```bash
echo -n 'export PATH=$HOME/bin:$PATH' >> ~/.zshrc
```

Read more about it [here](https://stackoverflow.com/questions/11530090/adding-a-new-entry-to-the-path-variable-in-zsh/47795375#47795375).

4. Add Latex formatter in VSCode.

```bash
sudo cpan Unicode::GCString
sudo cpan App::cpanminus
sudo cpan YAML::Tiny
sudo perl -MCPAN -e 'install "File::HomeDir"'
```

Read more about it [here](https://github.com/James-Yu/LaTeX-Workshop/issues/376#issuecomment-372497291).

### Code formatting

Run [Prettier](https://prettier.io/) to check formatting rules:

```bash
yarn prettier
```

Or to automatically format the code:

```bash
yarn prettier:write
```

**Note**: Prettier does not format `.tex` files.
