# codehub-readme-template

# Summary of what a README file is:

A README file contains important information about the associated source code, files, dependencies and related details that make up an application. In order to leverage applications and their associated source code, members of the open source community rely on clear and concise READMEs.

# Purpose of this template

The purpose of this README template is to provide project teams an easy template to copy-paste into their own README file for source code funded, either fully or partially, by the United States Department of Transportation (U.S. DOT) Intelligent Transportation Systems Joint Program Office (ITS JPO). This template contains elements for compliance with the [ITS JPO Source Code Guidelines](https://its.dot.gov/code/#/source-code-guidelines) and README best practices. All required fields must be filled out in order to make source code available on [ITS CodeHub](https://www.its.dot.gov/code/) and track compliance with the ITS JPO Source Code Guidelines. 

The goal is for project READMEs to be compliant, clear, concise, and informative for source code users. Please note that examples of the [CONTRIBUTING.md](https://github.com/usdot-jpo-codehub/codehub-readme-template/blob/master/Contributing.MD) and [LICENSE.md](https://github.com/usdot-jpo-codehub/codehub-readme-template/blob/master/LICENSE) files required by the ITS JPO Source Code Guidelines are nested within this template. See the License and Contributions sections of this template for more details. **Pease feel free to copy and paste this template into your own repository's README space.**

For a real-world example of an ITS JPO-funded project using this template, see the [STOL-AMS/TO-22-Improved-CACC](https://github.com/STOL-AMS/TO-22-Improved-CACC) repository.

# README Outline:
* Project Description
* Contact Information
* Release and Retention Notes
* Getting Started
* Prerequisites
* Installing
* Testing
* Deployment 
* Builds
* Contributions
* Versioning
* License
* Acknowledgments
* Additional Notes

# Project Description

*Required - Insert a description of your project, including the project's title, purpose and goals of the project, purpose of the source code, how the source code relates to the overall goals of the project, whether this source code relates to other source code in the project, and length of the project.*

Example:

README Template

This project is a README template for users to copy-paste into their project's README file and fill out with their project's information in order to provide useful and relevant information to users of a repository, as well as to be compliant with ITS JPO requirements for making source code available on ITS CodeHub. It is accompanied by a LICENSE and CONTRIBUTING file, linked to in the License and Contributions sections below. This project will continue indefinitely as long as the ITS JPO Source Code Guidelines are in effect.

## Contact Information

*Required - Provide a primary contact and associated contact information (e.g. email and phone number) for users to contact with questions about this repository.*

Example:

Contact Name: ITS JPO
Contact Information: data.itsjpo@dot.gov, (888)-888-8888

## Release and Retention Notes

*Required - A statement of the status of the source code (prototype, alpha, beta, release, etc.), how often users can expect activity on this repository, and a list of changes included in every release of your project. Additionally, a statement for how long this repository will remain publicly accessible*

Example:

Status: this project is in the release phase.

This project is updated approximately once every 2-3 weeks.

Retention: this project will remain publicly accessible for a minimum of five years (until at least 06/15/2025).

#### Release 1.0.0 (Mar 5, 2020)
- Initial release

#### Release 1.0.1 (Mar 19, 2020)
- Added unit tests
  - Unit tests can be run using `mvn clean test`
  
#### Release 1.0.2 (Apr 2, 2020)
- Fixed bug with popup

## Getting Started

*Required - Place instructions for standing up a copy of the project on a user's local machine for development and testing purposes. You can also include deployment notes for pushing to the production environment.*

### Prerequisites

*Detail what actions users need to take before they can stand up the project, including instructions for different environments users might have. This might include instructions and examples for installing additional software.*

Example:

Requires:
- Java 8 (or higher)
- Maven 3.5.4

### Installing

*Insert step-by-step instructions that a user needs to follow to stand up a development environment of your project.*

Example:

Step 1: Set up a cloud environment. 

```
Provide details. 
```

Step 2: Set up cloud alarms.

```
Provide details
```

## Testing

*Required - Provide explanation for how to run automated and manual tests for this project.*

### End-to-End Testing

*Detail each test and the reasoning behind it. It is also a best practice to provide several situational examples.*

Example:

To run the unit tests, run the following command:

```
mvn clean test
```

### Code standard tests

*Detail each test and the reasoning behind them. It is also a best practice to provide several situational examples.*

To run ESLint tests run the following command:

```
eslint myfile.js
```

## Deployment

*Optional - Add any additional notes users may need for how to deploy the project on a live system.*

Example:

Deploy this function as an AWS Lambda function, following [this guide](https://docs.aws.amazon.com/lambda/latest/dg/deploying-lambda-apps.html).

## Builds

*Required - Detail the open code standard(s) used, frameworks, and any applications used to create and run the project. If a non-open code standard is used, explain why.*

Example:
 
* [GNU Coding Standards](https://www.gnu.org/prep/standards/standards.html) - The open coding standard used
* [Dropwizard](https://www.dropwizard.io/en/latest/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributions

*Required - Create a file named "CONTRIBUTING.md" explaining how users can interact with this project's repository, your expectations for their conduct, and how contributions by users will be released (e.g. whether they will be released under the same license and whether those contributors waive their rights accordingly). See [CONTRIBUTING.md](https://github.com/usdot-jpo-codehub/codehub-readme-template/blob/master/Contributing.MD) for an example of this file.*

Example:

Please read [CONTRIBUTING.md](https://github.com/usdot-jpo-codehub/codehub-readme-template/blob/master/Contributing.MD) for details on our Code of Conduct, the process for submitting pull requests to us, and how contributions will be released.

## Versioning

*Optional - use this section to explain what versioning technique your project uses and how major and minor versions differ.*

Example:

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## License

*Required - Create a file named "LICENSE.md" that contains at least the licensing status of the code and the full text of the open source license or a link to where the license is officially maintained. If for some reason the source code does not use an open license, explain why. See [LICENSE.md](https://github.com/usdot-jpo-codehub/codehub-readme-template/blob/master/LICENSE) for an example of this file.*

Example:

This project is licensed under the Creative Commons 1.0 Universal (CC0 1.0) License - see the [License.MD](https://github.com/usdot-jpo-codehub/codehub-readme-template/blob/master/LICENSE) for more details. 

## Acknowledgments

*Required - describe how users should reference your code if they use it to build additional software, list the Digital Object Identifier for this project, and (optional) list if you have a 3rd party or any specific contributor to give credit.*

Example:

To track how this government-funded code is used, we request that if you decide to build additional software using this code please acknowledge its Digital Object Identifier in your software's README/documentation.

Digital Object Identifier: (fill in with DOI)

Shout out to [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2) for their README template.

## Additional Notes

*Optional - include any other relevant technical details on how to build, make, install or use the software, including dependencies. If there are datasets and associated Data Management Plans that interact with this source code, please provide them here.*
