# SEO fixes for Google Blogger Contempo template
## Current SEO issues with Contempo template
Contempo template is adding one \<h1> heading to every blog page. The heading contains the name of the blog, and in other pages than the
index page, it links back to the index. By default archive pages and search labels are not marked **noindex** causing a huge amount of duplicate content that has no relevance to search engines. There are meta tags missing for example for sharing on Twitter and on Facebook, and the template does not specify the language of the blog.
To fix these issues, I have created an updated SEO friendly version of the template. You can view it live at my <a href="https://www.travel-blog.2globalnomads.info/">travel blog</a>.
## Installation instructions
1. Download the [template.xml](template.xml) and edit it
2. Login to [Blogger](https://www.blogger.com)
3. Select your blog and click **Template**
4. Click **Backup/Restore**
5. Browse the template from your computer and click **Upload**
6. Select **Theme**, **Customize**, **Advanced**, **Add CSS** and copy [custom.css](custom.css) to **Add custom CSS** field. Click **Apply to Blog**. 
## Issues
#### Template has no AdSense support
I was not able to edit the template before I removed AdSense widgets. They were causing **Error 500** due to invalid widget settings. As it does not work on my blog, this template does not include any AdSense code.
