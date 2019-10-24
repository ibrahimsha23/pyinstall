# pyinstall
package to install python packages


Purpose:

Build a utility library to solve the  purpose of installing python packages
## Existing
  1. pip install -r requirements.txt will install line by line
  
## Proposal
  1. Hold the requirements in json file as npm install holds
  2. by entering pyinstall flask==1.0.0 --save-dev
      ```
          {
            "name": "core",
            "version": "0.0.1",
            "custom_pypi_org": true,
            "custom_pypi_org_link": "https://ibrahimsha.com/pypi.org",
            "dependencies": {
              "aws-sdk": "^2.547.0"
            },
            "devDependencies": {
              "flask": "^1.0.0"
            }
          }
      ```
 3. This will avoids using of multiple requirements file.
