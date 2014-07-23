# Predawn theme for Atom.
This is a theme for Atom. It's based on [Predawn](https://github.com/jamiewilson/predawn).

# Installation
This theme is not (yet) available from the package management system.
You can clone this package from here with:

    cd ~/.atom/packages
    git clone git@github.com:johman10/Predawn-Atom.git

After that you can change the UI theme within the settings of Atom.

# Settings
If you would like settings like in the original theme you can add the following lines to your stylesheet (Atom > Open your stylesheet).

    // Height of tabs
    @tab-height: 50px;

    // Height of tree items
    @tree-height: 25px;

    // Assigning variables
    .list-item {
      line-height: @tree-height !important;
    }

    .tab-bar {
      height: @tab-height;
      line-height: @tab-height;

      .tab {
        height: @tab-height;
      }
    }
