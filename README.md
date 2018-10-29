# Seniors Campaign Page

This repo is being used to build the Seniors Campaign pages. These Campaign pages are scheduled to launch on November 21st 2018 on the Canada.ca website. It is expected that the Campaign pages will be removed from the Canada.ca website around July 2019. 

## Preview Links 

* [English Seniors Campaign Page (Version 1) TO DO](#TODO)

* [French Seniors Campaign Page (Version 1) TO DO](#TODO)

## Building / Customising the Project 

The following instructions can be used to build and customise these campaign pages:

* Download the Project Files and drop them in a directory of your choosing
* Download and install the latest version of [Hugo](https://gohugo.io/)
* Navigate to your directory and in a command line type:

  `hugo server --disableFastRender`

* The command above will launch a local web server that you can use to preview your changes
* Modify the files in your directory using your favourite text editor 
* Check out the results on the localhost server that [Hugo](https://gohugo.io/) runs

## Ingredients for the Project 

### CSS

As a general rule, Bootstrap and WET ultility classes were used as a first step, and then anything I couldn't do with those base styles I wrote custom CSS to fill in the gaps.  

All campaign page content was wrapped in a scope class which reduces the risk of these CSS messing up other content should this file incorrectly be referenced. The scope class can be found at the start of the CSS file. 

If you are interested in the CSS you can find it here: 

* [CSS File](https://github.com/neilmispelaar/canada-ca-adult-campaign-page/blob/master/static/css/adult-campaign.css) 

### HTML 

Nothing overly special was done with the HTML. 

You can find the source for the pages here: 

* [English Seniors Campaign Page (Version 1) TO DO](#TODO)

* [French Seniors Campaign Page (Version 1) TO DO](#TODO)

### JavaScript

No custom JavaScript was used in the development of this project. 

### Tools 

* Build Engine: [Hugo.io](https://gohugo.io/)
* WET Template: [CDTS v4.0.28](https://ssl-templates.services.gc.ca/app/cls/wet/gcweb/v4_0_28/)
* CI and Hosting: [Netlify](https://www.netlify.com/)

## License

MIT
