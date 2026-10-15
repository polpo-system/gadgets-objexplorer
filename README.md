# gadgets-objexplorer

ObjExplorer for the gadgets of [polpo](https://github.com/polpo-system/polpo): shows the objects a
gadget is made of (its children, models and links) as a tree in a list.

```
portia.Install gadgets-objexplorer
```

## Using

    Desktops.OpenDoc ObjExplorer.Panel    the explorer; mark (*) a gadget, then Inspect on the
                                          panel lists its objects

## What is here

    src/ObjExplorer.Mod        the explorer
    share/ObjExplorer.Panel    its panel
    tools/ObjExplorer.Tool
    test/ObjExplorerTest.Mod

ObjExplorer is by Emil Zeller. The source comes from ETH Linux Oberon (OLR, 2017-06-18), converted from an Oberon text to plain
text; the first commit has it unchanged. It compiles unchanged with all five of polpo's compilers
(x86, ARM, ARMv7, RISC-V, MIPS).

## Tests

    ObjExplorerTest.Run      2 checks: the module loaded, its panel opened; it needs the
                             desktop's display

The license is GPL-3 (`LICENSE`); the code comes from ETH Oberon, whose license (`LICENSE.ETH`)
asks to keep its copyright notice and conditions, which `LICENSE.ETH` does.
