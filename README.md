# _Amazon Web Services_ Helper Scripts
A set of scripts designed to ease the pain of working with _Amazon Web Services_ (EC2 and S3). [Based on _Sean Bannister's_ original](https://github.com/SeanBannister/aws-helper-scripts).

---

`i-create-volume`

Create an EBS Volume. Then call `i-attach-volume` to Attach, Format and Persistently Mount the EBS Volume

---

`i-attach-volume`

Attach, Format and Persistently Mount an EBS Volume

---

`ln-mv`

Move a directory to an EBS volume and symlink from the original location to the EBS location. If the EBS volume already contains the directory we're trying to move to it just delete the original directory and create a symlink.

---

# Credit

_[Based on _Sean Bannister's_ original](https://github.com/SeanBannister/aws-helper-scripts)._ 

Thanks goes entirely to _Sean Bannister_:

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
| [<img src="https://avatars1.githubusercontent.com/u/197231" width="100px;"/><br /><sub>Sean Bannister</sub>](https://github.com/SeanBannister)<br />[📖](https://github.com/SeanBannister/aws-helper-scripts/commits?author=SeanBannister) |
| :---: |

<!-- ALL-CONTRIBUTORS-LIST:END -->

Contributions of any kind are welcome!

>## AWS Helper Scripts
>By Sean Bannister (www.SeanBannister.com)
>
>s3 scripts were originally developed by Raphael James Cohn as part of s3-bash (http://code.google.com/p/s3-bash/)
>
>These scripts were designed to simplify interaction with AWS on an EC2 instance.
