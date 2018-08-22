EndPoints: para probarlo hay que ejecutarlo desde el postman y agregar el header "api-version". Si no se pasa el header, utiliza por default la version 1
	Version 1
		Agrear esto en el header del request -> api-version:1.0
		http://localhost:60388/api/persons
	Version 2
		Agrear esto en el header del request -> api-version:2.0
		http://localhost:60388/api/Persons

Packages NuGet
	Microsoft.AspNet.WebApi.Versioning