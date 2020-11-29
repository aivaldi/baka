# baka Application

## Integration software

The intention of this software is allow common user to manipulate easily complex data manipulation

It splited in tree main artifacts

### UI
Should be an intuitive UI application to allow users to upload theri data and allow them to easyliy manipulate them

### Backend API
Should be an API that allows the upload file, process and create information

### Proxy API
This API will be accessible to the user, will be the one that interacts with BackendAPI

The idea is to use Mule as proxy API to simplify the data upload using theris connection and also transformation
Backend API will be spring FW with Apache Spark to perform data operations
UI will be react
