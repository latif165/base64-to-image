# base64-to-image

# Convert Base64 To Image

# Just Copy the save_base64_image function

<code>
$base64_image_string = 'your image string';
<br/><br/><br/>
$output_file_without_extension = 'file name with out extension'; <br/><br/><br/>
// for example if you want output file as abc.png you have to just pass out abc as file name <br/><br/><br/>
$path_with_end_slash = '/uploads'; Don't use / after uploads folder.<br/><br/><br/>

save_base64_image($base64_image_string, $output_file_without_extension, $path_with_end_slash="")
</code>