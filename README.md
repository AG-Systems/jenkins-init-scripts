Jenkins Groovy Init Mixins
--------------------------

You can create a Groovy script file $JENKINS_HOME/init.groovy, or any .groovy file in the directory $JENKINS_HOME/init.groovy.d/
`
import jenkins.model.*;

// start in the state that doesn't do any build.
Jenkins.instance.doQuietDown();
`



