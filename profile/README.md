# Expected workflow

1) the group leader should **open an issue** with what you intend to do, giving it an explanatory title and a detailed description (you are strongly encouraged to use the labels to add details)
2) the group leader should **fork the main branch** into a local repository, making changes together with other members of teh group
3) the group leader should **open a pull request** to bring the changes made in the personal repository into the main
4) **wait** for one of the owner group members ([@MatteoPossamai](https://github.com/MatteoPossamai), [@DavideC03](https://github.com/DavideC03) and [@FrostWalk](https://github.com/FrostWalk)) of the GitHub organization to **accept the pull request** after a brief review

It's not necessary to contact us to have pull requests accepted, we receive a notification whenever one is opened, in case a request is rejected, the causes will be specified in a comment in the pull requst.
The ability to perform **push directly on the main** and **auto accept pull requests** has been **disabled**.

A system will soon be implemented that will publish the code on the Common Crate as soon as a change is made to the main.


# A note on Rustfmt
To avoid conflicts given by different code formatting, a configuration file for Rustfmt is present in the root of the project, follow this tutorial to enable RustFmt in JetBrains IDEs
https://github.com/rust-lang/rustfmt/blob/master/intellij.md
