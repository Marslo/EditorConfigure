EditorConfigure
===============

Configuration for Editors


## RubyMine:
### Settings:
- Appearance
    - Theme: Darcula
    - Font: Consolas / 12
- Editor
    - Colors & Fonts:
        - Primary Font: Consolas / 18 / 1.0
    - Console Font:
        - Primary Font: Conoslas / 14 / 1.0

## [Launch application with agent](http://ollivander.franzoni.eu/2011/02/03/pycharm-rubymine-and-idea-linux-desktop-entries/)
- IDEA
    <pre><code>$IDEA_JDK/bin/java -javaagent:agent.jar=IDEA $JVM_ARGS -Djb.restart.code=88 $IDEA_MAIN_CLASS_NAME $*</code></pre>
- PyCharm
    <pre><code>$PYCHARM_JDK/bin/java -javaagent:agent.jar=PyCharm $JVM_ARGS -Djb.restart.code=88 $PYCHARM_MAIN_CLASS_NAME $*</code></pre>
- RubyMine
    <pre><code>$RUBYMINE_JDK/bin/java -javaagent:agent.jar=RubyMine $JVM_ARGS -Djb.restart.code=88 $RUBYMINE_MAIN_CLASS_NAME $*</code></pre>
