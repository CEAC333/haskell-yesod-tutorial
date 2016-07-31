# Haskell Yesod Experiments

Experiments with the Haskell study group.

    # Start a new Yesod project
    stack new my-project yesod-sqlite
    cd my-project

    # Install and build
    stack build yesod-bin cabal-install --install-ghc
    stack build

    # Run server and view site
    stack exec -- yesod devel
    firefox http://localhost:3000/
