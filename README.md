# HomeAssistant - MelCloud

Add to home assistant support for mitsubishi air conditioner (MELCloud)

## Installing

- Create a folder in your home assistant <config_dir>/custom_components/melcloud/
- Copy melcloud.py in <config_dir>/custom_components/melcloud/climate.py


Edit configuration.yaml and add below lines:
	
    climate:
	  - platform: melcloud
		email: !secret melcloud_email
		password: !secret melcloud_password

Then Edit secret.yaml and add following lines, replace upper case words with your data

    melcloud_email: MY_EMAIL
    melcloud_password: MY_PASSWORD
    
## License

This project is licensed under the WTF License