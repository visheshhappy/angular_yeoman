# angular-yo

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.14.0.

## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.

# Installing instructions

1. install nodejs in ur system
2. install yeoman, bower and grunt using command
    sudo npm install yo bower grunt-cli.
    Refer http://yeoman.io/learning/index.html
3. Install required generators in yeoman using commnad 
	npm install generator:angular 
4. take a checkout and do grunt server
    It should open a port at 9000. Tu run use url : http://localhost:9000/

5. Use "grunt build" to create a dist folder. It will do the following :
	a.lint our code,
	b.run our tests,
	c.concatenate and minify our scripts and styles to save on those network requests,
	d.optimize images if we were using any,
	e.compile the output of any preprocessors we’re using, and
	f.generally make our application really lean.

6. To run the project using dist folder use command "grunt serve:dist"

#Tips

Use sudo npm install in the folder where package.json is there in case some dependencies are not resolved.