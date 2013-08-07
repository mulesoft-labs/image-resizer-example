## Image Resizer Example Mule Application

### Opening in Studio

- Install the Amazon S3 and SQS connectors Studio plugins using the "Help > Install New Software" feature.
The two plugins are in the "MuleStudio Cloud Connectors Update Site - http://repository.mulesoft.org/connectors/releases/2" update site. 

- Use the "Import > Mule > Maven-based Mule Project from pom.xml" feature, selecting the pom.xml of this project.

### Settings

Edit the `mule-app.properties` and put your AWS security credentials and SMTP configuration.

Note that the AWS credentials should be associated with a user that has at least the following permissions:

- Amazon S3 Full Access
- Amazon SQS Full Access
