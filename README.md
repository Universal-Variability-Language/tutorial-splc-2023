# Materials for UVL Tutorial at SPLC'23

During the tutorial we need different software which may require some time to download and install. To have a smoother experience during the tutorial, it would be great to start preparing the respective tools during the introduction. During the tutorial, we will need the following:


| Sessions  | Software               | Link                                                      | Notes                            |
|-----------|------------------------|-----------------------------------------------------------|----------------------------------|
| Session 1 | Visual Studio Code     | https://code.visualstudio.com/Download                    |                                  |
|           | UVLS                   | https://marketplace.visualstudio.com/items?itemName=caradhras.uvls-code | Install via internal marketplace |
|           | z3                     | https://github.com/Universal-Variability-Language/uvl-lsp | Instructions for different OS    |
|           | graphVIZ View          | https://marketplace.visualstudio.com/items?itemName=tintinweb.graphviz-interactive-preview | Optional visualization for FM    |
| Session 2 | FeatureIDE Pre-package | https://featureide.github.io/                             | Pre-packages version 3.10.0      |
| Session 3 |                        |                                                           |                                  |


## Session 1: Textual Editing with UVLS

UVLS is an LSP that enables syntax highlighting, autocompletion, semantic analyses, and configuration for UVL models. 
In the tutorial, we will use the LSP in VSCode.

### Relevant Links

* VSCode: https://code.visualstudio.com/
* VSCode extension for UVLS: https://marketplace.visualstudio.com/items?itemName=caradhras.uvls-code
* LSP repository, including instructions to install Z3: https://github.com/Universal-Variability-Language/uvl-lsp
* YouTube video showing basic usage: https://youtu.be/KhPfibPWliA
* GraphViz Extension https://marketplace.visualstudio.com/items?itemName=tintinweb.graphviz-interactive-preview 
* z3 Solver: https://github.com/Z3Prover/z3

### How to get started
1. First, we install the SMT solver Z3. See https://github.com/Universal-Variability-Language/uvl-lsp for instructions on how to build z3 on different operating systems. While the majority of the tutorial can still be performed without z3, we strongly recommend installing it for using model analysis and support for configuring.
2. Install VSCode from https://code.visualstudio.com/ or using your favorite package manager (e.g. snap).
3. In VSCode, open the *extensions* tab and search for UVLS.
3a. Alternatively, you can download the extension from https://marketplace.visualstudio.com/items?itemName=caradhras.uvls-code. Then install the extension via Extension Tab > ... >  Install from VSIX.
3b. Arch-based Linux: Install code-marketplace (AUR) to enable extensions in VSCode
4. Accept the automatic download for the LSP binary.
5. You can now edit .uvl files with the editing support of UVLS.
6. For the graphical viewer, you need to install the GraphViz Interactive Viewer extension in uvl: https://marketplace.visualstudio.com/items?itemName=tintinweb.graphviz-interactive-preview. The GraphViz extension can also be installed using the internal marketplace. 


## Session 2: Modeling UVL with FeatureIDE
FeatureIDE is a widely used environment integrated in Eclipse for feature-oriented software development. UVL models can read, stored, and graphically edited in FeatureIDE. Furthermore, FeatureIDE supports many advanced operations for feature-oriented software development that can be used with UVL.

During the first session, we built an UVL model together that looks similar to [this](https://github.com/Universal-Variability-Language/tutorial-splc-2023/blob/main/models/icecream-shared.uvl). You can also continue with this UVL model provided here.

### Relevant Links

* Homepage with prepackaged versions of Eclipse with FeatureIDE: https://featureide.github.io/
* FeatureIDE repository: https://github.com/FeatureIDE/FeatureIDE
* Java-based UVL parser used in FeatureIDE: https://github.com/Universal-Variability-Language/uvl-parser-java

### How to get started
1. Download pre-packaged Eclipse with FeatureIDE (v.3.10.0) from https://featureide.github.io/
2. Extract Eclipse and run it.
3. Create a new feature modeling project via New -> FeatureIDE Project
3a. Select the just created UVL model in the dialog to initialize the project with it.

## Session 3: Transforming UVL models with TraVarT


* TraVarT repository: https://github.com/SECPS/TraVarT
