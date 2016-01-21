#Overview of the Framework

The core of the framework is the Learning Records Warehouse (LRW).  This hold data about student learning activity, as well as data about the student. Universites and colleges can provide access to developers and applications to submit data to the LRW, and to retrieve it.

### Activity Data
Activity data is stored in xAPI (or Tincan Format).  For information on Tincan see [http://tincanapi.com/](http://tincanapi.com/).

Activity data is provided by application that students use. Currently this includes plugins for Moodle and Blackboard, with other plugins under development.

* [Moodle xAPI plugin] (https://github.com/jlowe64/moodle-logstore_xapi) (external link)

The framework defines a set of xAPI recipes for common activity data, and data submitted should conform to these recipies. Currently the following recipies are available.

* [VLE](https://github.com/jiscdev/xapi-vle) (external link)


### Student Data

Student data is stored against a standard data model. On universities and colleges can submit data to the LRW. Data is stored against a standard model, and authorised applications can access data via RESTful APIs.

The Universal Data Definition model is documented in Github.

`* [Universal Data Definition] (https://github.com/jiscdev/analytics-udd) (external link)
