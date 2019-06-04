# Summer of Docs 2019

## Getting Started:

Discussed task-
* Correctly navigating and understanding how to use theme.txt for theming [lib\theme]
* Understanding the importance and absolute need for proper documentation for the project on a slightly messy hybrid which might be overwhelming to the average user
* Having a hands-on to file-based theme editing
    * theme.txt
    * default.xml
* Accuracy checks:
    * Some of the operations have no effect
* Button graphics system explained thoroughly
* Documenting new installation methods [Pull 7145 and Pull 7124]
* Additional expansions to the project

#### theme.txt file
```
Hands-on test for familiarity + working confirmed for(accuracy) for:
buttons.status.font
header.text.selected.color
buttons.status.color


Produces NO effect confirmed for:
editor.url.style
```
#### default.xml file
```XML
Hands on test for familiarity + working confirmed for(accuracy) for:
<matchedBracket bg=>

Produces NO effect confirmed for:
<style token="RESERVED_WORD_2">
```
| Issue    | Elaborated     |
| -------- | -------------- |
| editor.lable.style | This is not found within version 1.8.9 to validate its accuracy |
| Page missing | Contribution rule page missing: https://github.com/per1234/asdf/blob/master/CONTRIBUTING.md |

___

Task additions: 
Average user might face the "write privileges missing" (like I did) while theming via text files. A properly documented solution can be added to the documentation.

Questions before proceeding with assigned tasks:</br>
1. What exactly are we supposed to do under "button graphics system will need to be more thoroughly explained."
1. For the documentation of the new installation options along with other documentation in general- Will we use GitHub markdown, Gatsby or is there something else in specific?
1. Should I initalize a draft for my GSoD'19 application with Arduino under this specific project
1.  To discuss project expansion possibilities and talk about dynamic updates and requests is there any chat room specific for GSoD (like slack) or any other medium for direct chat and development. If so, kindly add/invite me, if not, I'd suggest creating one such room :)

</br>
</br>
<i>Note: 
I created this document as my very first markdown page under experiment, explorations and demonstration of my quick learning skills. This is my first interaction with the organisation so I apologise in advance if I have inadvertently violated any style guidelines and will happily rectify any issues.  </i>





