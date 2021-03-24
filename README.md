# Vidyard Security Awareness Training
 
This is a public version of the Security Training material used internally at PagerDuty for their annual employee security training.

Vidyard's security team has used their mkdocs framework, some of the image assets, and the general flow of the content as a starting base for the Vidyard internal Security Awareness Training program. 

[![PagerDuty Security Training](screenshot.png)](https://sudo.pagerduty.com)


# Development
While Pagerduty used a local mkdocs installation for development of the content, Vidyard instead uses a docker container for this purpose. 

    docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material

Run the above command in the git repo, and connect to localhost:8000 to view 




## License
[Apache 2](http://www.apache.org/licenses/LICENSE-2.0) (See [LICENSE](LICENSE) file)

