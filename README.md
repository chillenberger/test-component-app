# test component. 
This is a very simple test component to publish to Code artifact.  First ensure you are connected to the desired CodeArtifact domain and repository. The domain and repo shoudl match teh "name" in package.json. 

dist files are already installed. 

If you make changes you must change the version in packages.json then rebuild using "npm run build", this will rebuild the files in the dist directory. 
then publish using "npm publish", only dist directory, package.json, and README.md will be published to package. 

Helpful references: 
https://levelup.gitconnected.com/publish-react-components-as-an-npm-package-7a671a2fb7f
https://aws.amazon.com/blogs/devops/publishing-private-npm-packages-aws-codeartifact/
https://docs.aws.amazon.com/codeartifact/latest/ug/getting-started-console.html