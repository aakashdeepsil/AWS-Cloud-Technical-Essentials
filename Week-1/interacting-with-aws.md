## Interacting with AWS

- Every action you make in AWS is an API call that is authenticated and authorized. In AWS, you can make API calls to services and resources through the AWS Management Console, the AWS Command Line Interface (CLI), or the AWS Software Development Kits (SDKs). 

### The AWS Management Console

- One way to manage cloud resources is through the web-based console, where you log in and click on the desired service. This can be the easiest way to create and manage resources when you first begin working with the cloud. 
- The services are placed in categories, such as compute, database, storage and security, identity and compliance.

### The AWS Command Line Interface (CLI)

- Consider the scenario where you run tens of servers on AWS for your application’s backend. You want to run a report to collect data from all of these servers. You need to do this programmatically every day because the server details may change. Instead of manually logging into the AWS Management Console and copying/pasting information, you can schedule an AWS Command Line Interface (CLI) script with an API call to pull this data for you.

- The AWS CLI is a unified tool to manage AWS services. With just one tool to download and configure, you control multiple AWS services from the command line and automate them with scripts. The AWS CLI is open-source, and there are installers available for Windows, Linux, and Mac OS. 

### AWS Software Development Kits (SDKs)

- API calls to AWS can also be performed by executing code with programming languages. You can do this by using AWS Software Development Kits (SDKs). SDKs are open-source and maintained by AWS for the most popular programming languages, such as C++, Go, Java, JavaScript, .NET, Node.js, PHP, Python, and Ruby.

- Developers commonly use AWS SDKs to integrate their application source code with AWS services. Let’s say the backend of the application runs in Python and every time it receives a cat photo, it uploads that photo to a storage service. This action can be achieved from within the source code by using the AWS SDK for Python.

## Resources

- https://docs.aws.amazon.com/awsconsolehelpdocs/latest/gsg/learn-whats-new.html
- https://aws.amazon.com/cli/
- https://aws.amazon.com/developer/tools/

