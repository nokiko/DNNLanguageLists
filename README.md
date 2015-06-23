# DNNLanguageLists
Resx files for localized language lists for DNN 7.3.3 and up

With version 7.3.3 of the DNN Platform you can now have localized lists. In a nutshell the way the localization works is by examining the App_GlobalResources directory to see if there’s a resource file with the name "List_[ListName]". For the countries list this will be "List_Country." and then the localization code for example : "List_Country.<strong>nl-NL</strong>.resx"

For more information see http://www.dnnsoftware.com/community-blog/cid/155072/new-list-localization-in-dnn-733

For the compilation of these files I used files from https://github.com/umpirsky/country-list

To use this simply copy the needed resx files to your DNN installattion App_GlobalResources directory and your country selectbox will be localized
