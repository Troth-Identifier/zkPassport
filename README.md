# zkPassport
A monorepo for all infrastructures of zkPassport



This structure separates functionalities into well-defined folders. Here's a breakdown of the folders:

worldcoin/: Code for integrating with Worldcoin's PoP protocol.

nfc/: Code for handling NFC communication and data processing from passports.

zkproofs/: Code for implementing and using zero-knowledge proofs.

ui/: Code for the user interface where users interact with zkPassport.

data/: Stores any application data, potentially encrypted passport information.

tests/: Unit and integration tests for your code.

requirements.txt: Lists all external libraries required for the project.

Dockerfile: Includes instructions for building a Docker image for containerized deployment.
