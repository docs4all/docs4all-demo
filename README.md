# docs4all demo

Yes, another static site generator for markdown but with **infinite left menu** instead two levels of mkdocs-material, docusaurus 2, justthedocs, etc

![](https://avatars.githubusercontent.com/u/101013016?s=400&u=e1ca8d2e0c8bb40784fa75586099e22050a42218&v=4)

## How it works?
For technical details go to the official repository:

https://github.com/docs4all/docs4all

## How to run?

- [For developers](https://github.com/docs4all/docs4all?tab=readme-ov-file#run-your-own-demo)
- [As static site](https://github.com/docs4all/docs4all?tab=readme-ov-file#publish-as-static-web)
- For server wtith docker

```
docker build -t my-site .
docker run -it --name my-site -p 8080:80 my-site
```

## For github.io pages

```
export DOCS4ALL_SITE_FOLDER=docs
npm install
npm run build
npm run publish
```

This will generate the static site in a folder called **docs** ready to be [configured](https://github.com/docs4all/docs4all/assets/3322836/a3f0a8c6-b161-4790-a8cc-998f64c1f7df) as github.io page

## Contributors

<table>
  <tbody>
    <td>
      <img src="https://avatars0.githubusercontent.com/u/3322836?s=460&v=4" width="100px;"/>
      <br />
      <label><a href="http://jrichardsz.github.io/">JRichardsz</a></label>
      <br />
    </td>    
  </tbody>
</table>
