## Serpent OS Packaging Recipes

### Repositories

The repositories follow a largely monorepo development pattern, where
stack complexity is managed by splitting into several smaller repositories.

##### main

Owned by: `dev:main`

    The majority of software in the distribution is packaged here.

##### kernel

Owned by: `dev:kernel`

    All kernel specific packaging including modules and initrd management.

##### toolchain

Owned by: `dev:toolchain`

    Includes the GNU and LLVM toolchains, and `ldc` for bootstrap purposes.

##### gnome

Owned by: `dev:gnome`

    Projects that are explicitly part of the GNOME upstream umbrella belong here.

##### plasma

Owned by: `dev:plasma`

    Plasma, Frameworks + Applications.
