pincode-india
====================

Node module to easily lookup any pincode details in India.

The pincode data used in this module is provided by data.gov.in

## Install using npm:

``` bash
npm install pincode-india
```

## Example usage

```javascript
var pincode = require('pincode-india');

pincode.lookup('tirurkad B.O');
/*[{ 
	officeName: 'tirurkad B.O',
	pincode: 679321,
	taluk: 'Perinthalmanna',
	districtName: 'Malapuram',
	stateName: 'KERALA' 
	}]*/


pincode.lookup(679321);
/*[{
	officeName: 'tirurkad B.O',
	pincode: 679321,
	taluk: 'Perinthalmanna',
	districtName: 'Malapuram',
	stateName: 'KERALA'
	}]*/
	
	
	var get = pincode.lookup(679321);
	if (!get.length === 0) return console.log('Not founded')
	console.log(get[0].officeName)
```

## Sources

The pincode data used in the module has been provided by data.gov.in.


## License

MIT