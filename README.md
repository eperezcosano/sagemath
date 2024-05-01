# sagemath
SageMath is an open-source project to create mathematical software that is a free alternative to proprietary, closed-source packages. One way to access it on the Internet is through the SageMathcell server, where code can be entered and evaluated. It can also be accessed as a web service for situations requiring more interactive access to the data output.

The URL for accessing the web API is https://sagecell.sagemath.org/service. The secure URL is necessary to avoid CORS errors. Appending a trailing slash to this URL produces an additional CORS error when retrieving data. The code to be executed must be URL encoded as a URL component, not a full URL. The encoded string is then POSTed to the server with a prefix code= and a JSON response returned with the result of the interaction.

## Usage

### Install

```
npm i sagemath
```

<hr>
<div style="text-align: center">
<a href="https://www.buymeacoffee.com/ethanpc" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
</div>