http://azimi.me/2015/07/16/split-swagger-into-smaller-files.html

https://www.npmjs.com/package/swagger-cli
https://github.com/apigee-127/swagger-tools/blob/master/docs/CLI.md
https://www.npmjs.com/package/gulp-swagger

process
<write spec>	->	gulp:watch	-> gulp:read/parse
								-> gulp:validate
								-> gulp:combine(jsonRefs)
								-> gulp:create:browsableAPI
								-> gulp:output