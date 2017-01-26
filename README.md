# Documentation
<br>
### To Update current Posts
1) Upload the instagram image in "posts" folder
2) visit "index.html" file and find "<!-- Photo Grid -->" section
3) Change the 'src' name to the path of the post that you want to upload i.e. "posts/img.extension" where 'img' is the name of the image and '.extention' is the extension of the image eg: .jpg/.png/.gif etc
4) change the 'alt' text to the "description of the image you are uploading"
5) Save
##### 6) Remember, only 3 posts can go under 1 division. A division here represents a row of 3 image posts.
<br><br>
### To Upload New Posts
1) Upload the instagram image in "posts" folder
2) visit "index.html" file and find "<!-- Photo Grid -->" section
3) then scroll down a little and find "<!-- New <div> above here -->" section
4) <b>Above this section</b>, copy & paste:
<div class="w3-third">
      <img src="posts/img.extension" style="width:100%" onclick="onClick(this)" alt="description of the image">
</div>
5)  Change the 'src' name to the path of the post that you want to upload i.e. "posts/img.extension" where 'img' is the name of the image and '.extention' is the extension of the image eg: .jpg/.png/.gif etc
6) change the 'alt' text to the "description of the image you are uploading"
7) Save
##### 8) Remember, only 3 posts can go under 1 division. A division here represents a row of 3 image posts. If you want to upload another post, copy and paste: <img src="posts/img.extension" style="width:100%" onclick="onClick(this)" alt="description of the image"> inside the ##### <div> </div> tag, under previous post and ensure that there are maximum 3 posts inside one division.
9) If a division is full, follow from step no. 1
