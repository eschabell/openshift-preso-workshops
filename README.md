Update: June 2018 moved to [Gitlab](https://gitlab.com/eschabell/openshift-preso-workshops)


Online Workshops 
----------------
A set of workshops you can host online.


Install with one click
----------------------
[![Click to  install OpenShift](http://launch-shifter.rhcloud.com/launch/light/Click to  install.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges[]=php-5.4&initial_git_url=https://github.com/eschabell/openshift-preso-workshops.git&name=workshops)


Manual setup on OpenShift
-------------------------
Create an account at http://openshift.redhat.com/

Create a PHP application

    rhc app create workshops -t php-5.4 --from-code git://github.com/eschabell/openshift-preso-workshops.git

That's it, you can now start your workshop at:

    http://workshops-$your_domain.rhcloud.com

![Cover Slide](https://raw.githubusercontent.com/eschabell/openshift-preso-workshops/master/cover.png)
