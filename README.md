# CustomTemplate
## The custom template I will start using + how to create one in Visual Studio 2022 (mostly just for me in case I forget) 
### If you want to create your own custom project
Step 0:   
Create the template, the starter project u want every time you start coding (for me, it includes a few libraries, but u can add whatever)   
<br /> <br />
Step 1:    
Go to Project Export Template (the third option before the last one). Add a name (It will be the final name of the template _so choose wisely_),add an image(optional and idk why it inverted the colours for me T_T) and a description (also optional)    
If u did everything right, your project should be saved in Visual Studio 2022\My Exported Templates   
<br /> <br />
Step 2(optional) :  
If u want to modify settings,u can unzip your Template file from My Exported Templates, go to .vstemplate, open it in Notepad++(Edit with Notepad++), and modify this portion to your liking  
!! this part should be written/pasted after  </ProjectSubType> and before  <SortOrder>1000</SortOrder>
```
  <LanguageTag>C++</LanguageTag>
	<PlatformTag>Windows</PlatformTag>
```
After u modify, zip the files    
<br /> <br />
Step 3:
Copy and paste the **zipped** file into Visual Studio 2022\Templates\ProjectTemplates(\C++,C#.....)
<br /> <br />  
### If you want to copy paste my project   
Just copy paste the .zip file into Visual Studio 2022\Templates\ProjectTemplates\C++

