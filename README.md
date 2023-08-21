# Materials for UVL Tutorial at SPLC'23

During the tutorial we need different software which may require some time to download and install. To have a smoother experience during the tutorial, it would be great to start preparing the respective tools during the introduction. During the tutorial, we will need the following:


| Sessions  | Software               | Link                                                      | Notes                            |
|-----------|------------------------|-----------------------------------------------------------|----------------------------------|
| Session 1 | Visual Studio Code     | https://code.visualstudio.com/Download                    |                                  |
|           | UVLS                   | https://marketplace.visualstudio.com/items?itemName=caradhras.uvls-code | Install via internal marketplace |
|           | z3                     | https://github.com/Universal-Variability-Language/uvl-lsp | Instructions for different OS    |
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

### How to get started
1. *Optional:* If you want to use semantic analyses, please install Z3 first. See https://github.com/Universal-Variability-Language/uvl-lsp for instructions on how to build z3 on different operating systems.
2. Install VSCode from https://code.visualstudio.com/ or using your favorite package manager.
3. In VSCode, open the *extensions* tab and search for UVLS.
4. Accept the automatic download for the LSP.
5. You can now edit .uvl files with the editing support of UVLS.


## Session 2: Modeling UVL with FeatureIDE
FeatureIDE is a widely used environment integrated in Eclipse for feature-oriented software development. UVL models can read, stored, and graphically edited in FeatureIDE. Furthermore, FeatureIDE supports many advanced operations for feature-oriented software development that can be used with UVL.

### Relevant Links

* Homepage with prepackaged versions of Eclipse with FeatureIDE: https://featureide.github.io/
* FeatureIDE repository: https://github.com/FeatureIDE/FeatureIDE
* Java-based UVL parser used in FeatureIDE: https://github.com/Universal-Variability-Language/uvl-parser-java

### How to get started
1. Download pre-packaged Eclipse with FeatureIDE (v.3.10.0) from https://featureide.github.io/
2. Extract Eclipse and run it.
3. Create a new feature modeling project via New -> FeatureIDE Project
4. Add your UVL model to this project

## Session 3: Transforming UVL models with TraVarT


* TraVarT repository: https://github.com/SECPS/TraVarT
