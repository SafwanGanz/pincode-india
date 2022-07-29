pincode-india
====================

Node module to easily lookup any pincode details in India.

The pincode data used in this module is provided by data.gov.in

## Install using npm:

``` bash
npm install github:SafwanGanz/pincode-india
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
```

## Sources

The pincode data used in the module has been provided by data.gov.in.


## License

MIT
