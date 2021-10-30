## packer ubuntu image

In this project we create ubuntu image with the power of packer, virtualbox.
for customization we can use any tool such as ansible, * scripts, chef , puppet and etc

you can make image from iso or another image, in this example we use iso , 
when we decided to use iso we should create answerfile (preseed file - file contain  answers to all question during os installation )

## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites


* Linux OS
* Packer
* virtualbox


### Building image

   ```sh
   git clone https://github.com/greenweb-cloud/packer-ubuntu-image
   cd packer-ubuntu-image
   packer build ubuntu-18.04.json
   ```
