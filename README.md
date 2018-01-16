# NG States
This project aims at gathering information about states in Nigeria. This information includes local governments areas, geolocation tags, population, etc. The goal of this project is to provide a json file that will provide some information about states in Nigeria for other projects.

## Data
This project has data about the states in the following format:
 - [JSON](data/ng.states.json) 
 	```json
 	{
	  "states": [
	    {
	      "code": "AB",
	      "name": "Abia",
	      "local_government_areas": [
	      	{
	          "code": "EZA",
	          "name": "Aba North"
	        },
	        ...
	      ]
	    }
	    ...
	  ]
	}
 	```

## License
This project is licensed under the GNU GPv3 License - see the [LICENSE](LICENSE) file for details
