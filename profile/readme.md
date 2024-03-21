# Vulnerabilities database (VDB)

The goal of this project is to manage the vulnerabilities of a computer park other than Excel.

Enjoy

## Run the project

### Directly on the machine

> Start from your preffered folder

```sh
# Create and go to the new folder
mkdir vdb
cd vdb

# Clone the components of the software
git clone https://github.com/vuln-database/vdb-front.git
git clone https://github.com/vuln-database/vdb-middle.git
git clone https://github.com/vuln-database/vdb-back.git

# Start the middleware
cd vdb-middle
npm install
#npm run --test
npm start
```
