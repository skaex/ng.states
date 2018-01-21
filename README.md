# NG States
This project aims at gathering information about states in Nigeria. This information includes local governments areas(with their official codes), official nicknames, official state codes, etc. The goal of this project is to provide a json file that will provide some information about states in Nigeria for other projects.

## Data
This project has data about the states in the following format:
 - [JSON](data/ng.states.json) 

## Description
The following is format of the information provided

### States

property                   | type   | description
---------------------------|--------|------------
`name`                     | string | Full name of state
`code`                     | string | Official state code
`nicknames`                | array  | Official nicknames of the state
`local_government_areas`   | array  | Array containing local governments under the state

### Local Governement Areas

property                   | type   | description
---------------------------|--------|------------
`name`                     | string | Full name of local government area
`code`                     | string | Official code


## License
This project is licensed under the GNU GPv3 License - see the [LICENSE](LICENSE) file for details
