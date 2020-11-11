<!--- DO NOT EDIT - Generated by ToolsLister at 2019-03-11T13:35:23.237-->
# Supported Report Formats

Jenkins' Warnings Next Generation Plugin supports the following report formats. 
If your tool is supported, but has no custom icon yet, please file a pull request for the
[Warnings Next Generation Plugin](https://github.com/jenkinsci/warnings-ng-plugin/pulls).
If your tool is not yet supported you can either define a new 
Groovy based parser in the user interface or provide a parser within a new small plugin. 
If the parser is useful for 
other teams as well please share it and provide pull requests for the 
[Warnings Next Generation Plug-in](https://github.com/jenkinsci/warnings-ng-plugin/pulls) and 
the [Analysis Parsers Library](https://github.com/jenkinsci/analysis-model/). 

| Number | ID | Symbol | Icons | Name | Default Pattern |
| --- | --- | --- | --- | --- | --- |
| 0 | acu-cobol | acuCobol() | - - | AcuCobol Compiler |  |
| 1 | gnat | gnat() | - - | Ada Compiler (gnat) |  |
| 2 | android-lint | androidLintParser() | ![Android Lint](src/main/webapp/icons/android-lint-24x24.png) ![Android Lint](src/main/webapp/icons/android-lint-48x48.png) | Android Lint |  |
| 3 | ansiblelint | ansibleLint() | - - | Ansible Lint |  |
| 4 | armcc | armCc() | - - | Armcc Compiler |  |
| 5 | aspectj | ajc() | - - | AspectJ Compiler |  |
| 6 | buckminster | buckminster() | - - | Buckminster |  |
| 7 | cadence | cadence() | - - | Cadence Incisive |  |
| 8 | ccm | ccm() | - - | CCM |  |
| 9 | checkstyle | checkStyle() | ![CheckStyle](src/main/webapp/icons/checkstyle-24x24.png) ![CheckStyle](src/main/webapp/icons/checkstyle-48x48.png) | [CheckStyle](https://checkstyle.org) | **/checkstyle-result.xml |
| 10 | clang | clang() | - - | Clang (LLVM based) |  |
| 11 | clang-tidy | clangTidy() | - - | Clang-Tidy |  |
| 12 | code-analysis | codeAnalysis() | - - | CodeAnalysis |  |
| 13 | codenarc | codeNarc() | - - | CodeNarc |  |
| 14 | coolflux | coolflux() | - - | Coolflux DSP Compiler |  |
| 15 | cpd | cpd() | ![CPD](src/main/webapp/icons/dry-24x24.png) ![CPD](src/main/webapp/icons/dry-48x48.png) | [CPD](https://pmd.github.io/latest/pmd_userdocs_cpd.html) | **/cpd.xml |
| 16 | cppcheck | cppCheck() | - - | CPPCheck |  |
| 17 | cpplint | cppLint() | - - | CppLint |  |
| 18 | csslint | cssLint() | - - | CssLint |  |
| 19 | detekt | detekt() | - - | [Detekt](https://arturbosch.github.io/detekt/) |  |
| 20 | docfx | docFx() | - - | DocFX |  |
| 21 | doxygen | doxygen() | - - | Doxygen |  |
| 22 | dr-memory | drMemory() | - - | Dr. Memory |  |
| 23 | eclipse | eclipse() | - - | Eclipse ECJ |  |
| 24 | erlc | erlc() | - - | Erlang Compiler (erlc) |  |
| 25 | error-prone | errorProne() | ![Error Prone](src/main/webapp/icons/bug-24x24.png) ![Error Prone](src/main/webapp/icons/bug-48x48.png) | [Error Prone](https://errorprone.info) |  |
| 26 | eslint | esLint() | ![ESlint](src/main/webapp/icons/eslint-24x24.png) ![ESlint](src/main/webapp/icons/eslint-48x48.png) | [ESlint](https://eslint.org) |  |
| 27 | findbugs | findBugs() | ![FindBugs](src/main/webapp/icons/findbugs-24x24.png) ![FindBugs](src/main/webapp/icons/findbugs-48x48.png) | FindBugs | **/findbugsXml.xml |
| 28 | flake8 | flake8() | - - | Flake8 |  |
| 29 | flex | flexSdk() | - - | Flex SDK Compiler |  |
| 30 | fxcop | fxcop() | - - | FxCop |  |
| 31 | gendarme | gendarme() | - - | Gendarme |  |
| 32 | ghs-multi | ghsMulti() | - - | GHS Multi Compiler |  |
| 33 | gcc3 | gcc3() | - - | GNU C Compiler 3 (gcc) |  |
| 34 | gcc4 | gcc4() | - - | GNU C Compiler 4 (gcc) |  |
| 35 | fortran | gnuFortran() | - - | GNU Fortran Compiler |  |
| 36 | golint | goLint() | ![Go Lint](src/main/webapp/icons/golint-24x24.png) ![Go Lint](src/main/webapp/icons/golint-48x48.png) | Go Lint |  |
| 37 | go-vet | goVet() | - - | Go Vet |  |
| 38 | groovy | groovyScript() | - - | Groovy Parser |  |
| 39 | iar-cstat | iarCstat() | - - | IAR C-STAT |  |
| 40 | iar | iar() | - - | IAR Compiler (C/C++) |  |
| 41 | xlc | xlc() | - - | IBM XLC Compiler |  |
| 42 | infer | infer() | - - | [Infer](http://fbinfer.com) |  |
| 43 | intel | intel() | - - | Intel Compiler (C, Fortran) |  |
| 44 | idea | ideaInspection() | ![IntelliJ IDEA Inspections](src/main/webapp/icons/idea-24x24.png) ![IntelliJ IDEA Inspections](src/main/webapp/icons/idea-48x48.png) | [IntelliJ IDEA Inspections](https://www.jetbrains.com/help/idea/code-inspection.html) |  |
| 45 | java | java() | ![Java](src/main/webapp/icons/java-24x24.png) ![Java](src/main/webapp/icons/java-48x48.png) | Java |  |
| 46 | javadoc-warnings | javaDoc() | ![JavaDoc](src/main/webapp/icons/java-24x24.png) ![JavaDoc](src/main/webapp/icons/java-48x48.png) | JavaDoc |  |
| 47 | jc-report | jcReport() | - - | JCReport |  |
| 48 | js-hint | jsHint() | - - | JSHint |  |
| 49 | jslint | jsLint() | - - | [JSLint](https://www.jslint.com) |  |
| 50 | klocwork | klocWork() | - - | Klocwork |  |
| 51 | ktlint | ktLint() | ![Ktlint](src/main/webapp/icons/ktlint-24x24.png) ![Ktlint](src/main/webapp/icons/ktlint-48x48.png) | [Ktlint](https://ktlint.github.io) |  |
| 52 | maven-warnings | mavenConsole() | - - | Maven |  |
| 53 | taglist | tagList() | - - | [Maven Taglist Plugin](https://www.mojohaus.org/taglist-maven-plugin) | **/taglist.xml |
| 54 | metrowerks | metrowerksCodeWarrior() | - - | Metrowerks CodeWarrior |  |
| 55 | msbuild | msBuild() | - - | MSBuild |  |
| 56 | mypy | myPy() | - - | MyPy |  |
| 57 | nag-fortran | nagFortran() | - - | NAG Fortran Compiler |  |
| 58 | open-tasks | taskScanner() | ![Open Tasks Scanner](src/main/webapp/icons/open-tasks-24x24.png) ![Open Tasks Scanner](src/main/webapp/icons/open-tasks-48x48.png) | Open Tasks Scanner | - |
| 59 | invalids | invalids() | - - | Oracle Invalids |  |
| 60 | pclint | pcLint() | - - | PC-Lint |  |
| 61 | pep8 | pep8() | - - | Pep8 |  |
| 62 | perforce | perforce() | - - | Perforce Compiler |  |
| 63 | perl-critic | perlCritic() | - - | Perl::Critic |  |
| 64 | php | php() | - - | PHP Runtime |  |
| 65 | php-code-sniffer | phpCodeSniffer() | - - | [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) |  |
| 66 | pit | pit() | ![Pit Test Coverage](src/main/webapp/icons/pit-24x24.png) ![Pit Test Coverage](src/main/webapp/icons/pit-48x48.png) | [Pit Test Coverage](http://pitest.org) |  |
| 67 | pmd | pmdParser() | ![PMD](src/main/webapp/icons/pmd-24x24.png) ![PMD](src/main/webapp/icons/pmd-48x48.png) | [PMD](https://pmd.github.io) | **/pmd.xml |
| 68 | prefast | prefast() | - - | PREfast |  |
| 69 | puppetlint | puppetLint() | - - | Puppet-Lint |  |
| 70 | pydocstyle | pyDocStyle() | - - | Pydocstyle |  |
| 71 | pylint | pyLint() | ![Pylint](src/main/webapp/icons/pylint-24x24.png) ![Pylint](src/main/webapp/icons/pylint-48x48.png) | Pylint |  |
| 72 | qac | qacSourceCodeAnalyser() | - - | QA-C Sourcecode Analyser |  |
| 73 | dupfinder | dupFinder() | ![Resharper dupFinder](src/main/webapp/icons/dry-24x24.png) ![Resharper dupFinder](src/main/webapp/icons/dry-48x48.png) | Resharper dupFinder |  |
| 74 | resharper | resharperInspectCode() | ![Resharper InspectCode](src/main/webapp/icons/resharper-24x24.png) ![Resharper InspectCode](src/main/webapp/icons/resharper-48x48.png) | Resharper InspectCode |  |
| 75 | robocopy | robocopy() | - - | Robocopy |  |
| 76 | rflint | rfLint() | ![Robot Framework Lint](src/main/webapp/icons/robot-framework-24x24.png) ![Robot Framework Lint](src/main/webapp/icons/robot-framework-48x48.png) | Robot Framework Lint |  |
| 77 | rubocop | ruboCop() | ![RuboCop](src/main/webapp/icons/rubocop-24x24.png) ![RuboCop](src/main/webapp/icons/rubocop-48x48.png) | RuboCop |  |
| 78 | scala | scala() | ![Scala Compiler](src/main/webapp/icons/scala-24x24.png) ![Scala Compiler](src/main/webapp/icons/scala-48x48.png) | Scala Compiler |  |
| 79 | simian | simian() | ![Simian](src/main/webapp/icons/dry-24x24.png) ![Simian](src/main/webapp/icons/dry-48x48.png) | Simian |  |
| 80 | sonar | sonarQube() | ![SonarQube](src/main/webapp/icons/sonar-24x24.png) ![SonarQube](src/main/webapp/icons/sonar-48x48.png) | SonarQube | **/sonar-report.json |
| 81 | sphinx | sphinxBuild() | - - | Sphinx-build |  |
| 82 | spotbugs | spotBugs() | ![SpotBugs](src/main/webapp/icons/spotbugs-24x24.png) ![SpotBugs](src/main/webapp/icons/spotbugs-48x48.png) | [SpotBugs](https://spotbugs.github.io) | **/spotbugsXml.xml |
| 83 | stylecop | styleCop() | - - | StyleCop |  |
| 84 | sunc | sunC() | - - | SUN C++ Compiler |  |
| 85 | swiftlint | swiftLint() | - - | [SwiftLint](https://github.com/realm/SwiftLint) |  |
| 86 | tasking-vx | taskingVx() | - - | TASKING VX Compiler |  |
| 87 | code-composer | tiCss() | - - | Texas Instruments Code Composer Studio |  |
| 88 | tnsdl | tnsdl() | - - | TNSDL Translator |  |
| 89 | tslint | tsLint() | - - | [TSLint](https://palantir.github.io/tslint/) |  |
| 90 | diabc | diabC() | - - | Wind River Diab Compiler (C/C++) |  |
| 91 | xmllint | xmlLint() | - - | XML Lint |  |
| 92 | yamllint | yamlLint() | - - | [YamlLint](https://yamllint.readthedocs.io/) |  |
| 93 | yui | yuiCompressor() | - - | YUI Compressor |  |
| 94 | zptlint | zptLint() | - - | ZPT Lint |  |