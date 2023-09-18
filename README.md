# WordPress Quick
WordPress Quick setup with WPCLI for local development

## Installing
Copy and execute following command to install WordPress Quick
```
wget -qO uc https://raw.githubusercontent.com/enishant/wq/master/wq && sudo bash wq
```

## Usage
Use WordPress Quick with following command arguments
```
wq <project_name> <database_user> <database_password> <base_url>
```

## Example(s):
If database username & password is "root" and base url host is "localhost"
```
wq myproject
```

If database username & password are different than "root" 
```
wq myproject mydbuser mydbpass
```

If database username & password are different than "root" and base url is not "localhost"
```
wq myproject dbuser dbpass http://example.com
```

## Contributing
All contributions for enhancement and fixes will be accepted through pull request, you can also contribute by reporting issues, [Click here](https://github.com/enishant/wq/issues/new) to report an issue.

## License
WordPress Quick is released under the MIT License. See [LICENSE](LICENSE) file for more details.
