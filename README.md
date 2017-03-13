#SwiftlintYamlFile

Follow these steps for **SwiftLint** integration:

1. Install [SwiftLint](https://github.com/realm/SwiftLint) (preferred via Cocoapods) in project
2. Open terminal:
   * `cd path/to/project`
   * `$ git submodule add /url/submodule/<reponame>`
   * `$ ln -s <reponame>/path/to/<linked_file>`
   * `$ git add .gitmodules <linked_file>`
   * `$ git commit -m "add a symbolic link to <linked_file> with the respective submodule"`
   * Push that commit and enjoy :+1:
