## Wordpress and Git 

Integrating git workflow with wordpress. WordPress is set as a submodule. Content directory and wp-config are also move into the root directory. This base skeleton is included with theme twentythirteen.

### How to use
* Clone the repository `git clone https://github.com/ahmadshah/wp-git.git`
* Run `git submodule init`
* Run `git submodule update` to fetch WordPress
* Browse to `http://localhost/wp/wp-admin` and start the installation
* Rename `wp-config-sample.php` to `wp-config.php` and replace the required values
