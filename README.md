FORMAT: 1A
HOST: http://mongohouse.io

For detailed documentation, please visit https://mongohouse.docs.apiary.io

![MongoHouse Data Sharing](https://pbs.twimg.com/media/DSZzUvOWAAEXeOw.jpg)



### What is metadata, why is MongoHouse sharing only metadata?

Wikipedia's explanation of "Metadata":

> Metadata is "data [information] that provides information about other data".[1] Three distinct types of metadata exist: descriptive metadata, structural metadata, and administrative metadata.[2]
> Descriptive metadata describes a resource for purposes such as discovery and identification. It can include elements such as title, abstract, author, and keywords.
> Structural metadata is metadata about containers of data and indicates how compound objects are put together, for example, how pages are ordered to form chapters. It describes the types, versions, relationships and other characteristics of digital materials. [3]
> Administrative metadata provides information to help manage a resource, such as when and how it was created, file type and other technical information, and who can access it.[4]

This set of APIs does not provide the actual data, but rather the metadata of the actual data. It provides an interface for developers to query the GTA's soldrecords. 

### This set of APIs is good for, for example:

1. building analytic applications;
2. creating a report using data aggregation and re-organization;
3. feeding an AI framework to do machine learning/traning and make market prediction. 

### This set of APIs is NOT good for:

However, this set of APIs is not suitable for creating an application to display and look up for single data point. Some of the key information is intentionally hashed for a number of reasons: 

1. MongoHouse does not own the copyright of the data;
2. MongoHouse can not guarantee the integrity of the data;
3. MongoHouse does not have a way to control how the data is re-distributed.

### Purpose of this project

This API set is provided as a pilot test project, in order to learn: 

1. if the demand is strong;
2. if the data set is meaningful with the selected fields;
3. if there are any legal/privacy concerns regarding this platform of data decentralization.

### Data Synchronization Schedule

mongohouse.io gets indexed on every 15th day of the month, for previous month's metadata set. The metadata is roughly 6 weeks behind mongohouse.com's main database.

### To Get Started

1. Create a mongohouse.io account: http://mongohouse.io/authentication/signup;
2. Get comfortable with the APIs: https://mongohouse.docs.apiary.io/#.

### Project Status

This project is currently work-in-progress, and won't get heavily focused on until: 

1. Strong interest drives extra funding for resource (engineering resource and infrastructure resource);
2. Proven useful and meaningful;
3. Externally acquired/funded by third-party who is willing to take ownership/co-ownership of the project.

### Help

Please email io@mail.mongohouse.com for help.

### Bugs and Issues

Please use https://github.com/mongohouse/mongohouse.io/issues to report bugs.

### License

License for this project: MIT (https://opensource.org/licenses/MIT)

License for the metadata set: GPLv3 (Tentatively, https://www.gnu.org/licenses/quick-guide-gplv3.en.html)

### Contribution

Please email contribution@mail.mongohouse.com to get in touch with the core development team.
