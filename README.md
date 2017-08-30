# Danta - Parent Project

Danta is the agnostic multi-platform templating engine. enables developers and IT teams to use technologies they already know, expediting the creation and leveraging of reusable technical assets.

Danta - Parent Project is the maven parent project to all Danta projects.

## Prerequisites

 * Java 8
 * AEM 6.2 or later (for integration with AEM)
 * For AEM only: [ACS AEM Commons 3.9.0](https://github.com/Adobe-Consulting-Services/acs-aem-commons/releases/tag/acs-aem-commons-3.9.0) or later
 * Jahia 7.2 or later (for integration with Jahia)

## Documentation

### Installation

#### Adobe Experience Manager (AEM)

  * Via AEM Package Manager, install [ACS AEM Commons 3.9.0](https://github.com/Adobe-Consulting-Services/acs-aem-commons/releases/tag/acs-aem-commons-3.9.0) or later
  * Clone the following repositories into the same folder (i.e. C:\workspace\danta or /User/{username}/workspace/danta) 
  then run the maven build command (refer to **Compile** section of README.md, for each repository) in the following order
    * [Parent](https://github.com/DantaFramework/Parent)
    * [API](https://github.com/DantaFramework/API)
    * [Core](https://github.com/DantaFramework/Core)
    * [AEM](https://github.com/DantaFramework/AEM)
    * [AEM Demo](https://github.com/DantaFramework/AEMDemo)   

### Jahia

  * Clone the following repositories into the same folder (i.e. C:\workspace\danta or /User/{username}/workspace/danta) 
    then run the maven build command (refer to **Compile** section of README.md, for each repository) in the following order
    * [Parent](https://github.com/DantaFramework/Parent)
    * [API](https://github.com/DantaFramework/API)
    * [Core](https://github.com/DantaFramework/Core)
    * [JahiaDF](https://github.com/DantaFramework/JahiaDF)
    * [JahiaDF Demo](https://github.com/DantaFramework/JahiaDFDemo)

### Official documentation

 * Read our [official documentation](http://danta.tikaltechnologies.io/docs) for more information.

## License

Read [License](LICENSE) for more licensing information.

## Contribute

Read [here](CONTRIBUTING.md) for more information.

## Compile

    mvn clean install
    
    
## Credit

Special thanks to Jose Alvarez, who named Danta for the powerful ancient Mayan pyramid, La Danta. 
La Danta is the largest pyramid in El Mirador—the biggest Mayan city found in Petén, Guatemala.