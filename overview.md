#Overview of the Framework

The core of the framework is the Learning Records Warehouse (LRW).  
This hold data:
* about student learning activity (in xAPI format)
* about the student. (in Jisc UDD format)

Universites and colleges can provide access to developers and applications to submit data to the LRW, and to retrieve it.

This data can be used for predicative analytics, to provide dashboards for staff and students, and to build any other learning application that can make use of this data set, as long is it complies with [https://www.jisc.ac.uk/guides/code-of-practice-for-learning-analytics] (Jisc's Learning Analytics code of practice)

### Activity Data
Activity data is stored in xAPI (or Tincan Format).  For information on Tincan see [http://tincanapi.com/](http://tincanapi.com/).

Activity data is provided by application that students use. Currently this includes plugins for Moodle and Blackboard, with other plugins under development.

* [Moodle xAPI plugin] (https://github.com/jlowe64/moodle-logstore_xapi) (external link)

The framework defines a set of xAPI recipes for common activity data, and data submitted should conform to these recipies. Currently the following recipies are available.

* [VLE](https://github.com/jiscdev/xapi-vle) (external link)

More information about about activity data is available on [activity-data.md](activity-data.md)


### Student Data

Student data is stored against a standard data model. On universities and colleges can submit data to the LRW. Data is stored against a standard model, and authorised applications can access data via RESTful APIs.

The Universal Data Definition model is documented in Github.

`* [Universal Data Definition] (https://github.com/jiscdev/analytics-udd) (external link)
