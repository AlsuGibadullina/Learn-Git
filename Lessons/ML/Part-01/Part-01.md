# Git - അടിസ്ഥാന നാവിഗേഷൻ  

- [പരിചയം](#introduction)  
- [BASH ടെർമിനൽ തുറക്കൽ](#opening-the-bash-terminal)  
- [ഡയറക്‌ടറികൾ വഴി സഞ്ചാരിക്കൽ](#navigating-through-directories)  
- [ഡയറക്‌ടറി ഉള്ളടക്കങ്ങൾ പട്ടികവത്കരിക്കൽ](#listing-directory-contents)  
- [ഡയറക്‌ടറികൾ സൃഷ്ടിക്കുകയും നീക്കം ചെയ്യുകയും ചെയ്യുക](#creating-and-removing-directories)  
- [ഫയലുകൾ സൃഷ്ടിക്കുകയും നീക്കം ചെയ്യുകയും ചെയ്യുക](#creating-and-removing-files)  
- [ഉപസംഹാരം](#conclusion)  

## പരിചയം  

BASH ടെർമിനൽ ഒരു ശക്തമായ കമാൻഡ്-ലൈൻ ഇന്റർഫേസ് ആണുയോജകർക്ക് അവരുടെ കമ്പ്യൂട്ടറിന്റെ ഫയൽ സിസ്റ്റം നാവിഗേറ്റ് ചെയ്യാനും, വിവിധ ജോലികൾ നടത്താനും, Git പോലുള്ള വേർഷൻ കൺട്രോൾ സിസ്റ്റങ്ങളുമായി പ്രവർത്തിക്കാനുമാകുന്നു. Git ഒരു വ്യാപകമായി ഉപയോഗിക്കുന്ന ഡിസ്‌ട്രിബ്യൂട്ടഡ് വേർഷൻ കൺട്രോൾ സിസ്റ്റമാണ്, ഇത് കോഡ് റീപോസിറ്ററികളിലെ മാറ്റങ്ങൾ മികച്ച രീതിയിൽ കൈകാര്യം ചെയ്യാനും സഹകരിക്കാനുമുള്ള കഴിവ് നൽകുന്നു. ഈ ലേഖനത്തിൽ, BASH ടെർമിനൽ ഉപയോഗിച്ച് Git പ്രവർത്തനക്ഷമമാക്കുന്നതിനുള്ള അടിസ്ഥാന കമാൻഡുകൾ എങ്ങനെ ഉപയോഗിക്കാമെന്നത് പരിശോധിക്കാം.  

## BASH ടെർമിനൽ തുറക്കൽ  

ആദ്യമായി, നിങ്ങളുടെ ഇഷ്ടപ്പെട്ട ടെർമിനൽ അപ്ലിക്കേഷൻ തുറക്കുക. മിക്ക Unix-ആധാരിത സിസ്റ്റങ്ങളിലും, ഇത് "Applications" അല്ലെങ്കിൽ "Utilities" ഫോളിഡറുകളിൽ കണ്ടെത്താം. ടെർമിനൽ തുറന്നാൽ, കമാൻഡ് പ്രോംപ്റ്റ് പ്രത്യക്ഷപ്പെടും, നിങ്ങളുടെ കമാൻഡുകൾ സ്വീകരിക്കാൻ തയ്യാറായിരിക്കും.  

## ഡയറക്‌ടറികൾ വഴി സഞ്ചാരിക്കൽ  

**pwd** കമാൻഡ് ഉപയോഗിച്ച് നിലവിലെ പ്രവർത്തന ഡയറക്‌ടറിയുടെ പാത്ത് പ്രിന്റ് ചെയ്യാം:  
```commandline
pwd
```  
**cd** കമാൻഡ് ഉപയോഗിച്ച് ഡയറക്‌ടറികൾക്കിടയിൽ നീങ്ങാം:  

- ഒരു ഡയറക്‌ടറിയിലേക്ക് പ്രവേശിക്കാൻ:  
  ```commandline
  cd Documents
  ```  
- ഒരു തല തിരികെയാകാൻ:  
  ```commandline
  cd ..
  ```  
- ഹോം ഡയറക്‌ടറിയിലേക്ക് പോകാൻ:  
  ```commandline
  cd ~
  ```  
- മുമ്പ് സന്ദർശിച്ച ഡയറക്‌ടറിയിലേക്ക് തിരികെ പോകാൻ:  
  ```commandline
  cd -
  ```  

## ഡയറക്‌ടറി ഉള്ളടക്കങ്ങൾ പട്ടികവത്കരിക്കൽ  

**ls** കമാൻഡ് ഡയറക്‌ടറിയിൽ ഉള്ള ഫയലുകളും ഫോൾഡറുകളും കാണിക്കുന്നു:  

- വിശദമായ പട്ടിക പ്രദർശിപ്പിക്കാൻ:  
  ```commandline
  ls -l
  ```  
- മറഞ്ഞിരിക്കുന്ന ഫയലുകൾ കാണിക്കാൻ:  
  ```commandline
  ls -a
  ```  
- ഫയലുകളുടെ വലിപ്പം മനസ്സിലാക്കാൻ എളുപ്പമുള്ള രൂപത്തിൽ കാണിക്കാൻ:  
  ```commandline
  ls -h
  ```  
- എല്ലാവിധ സബ്ഡയറക്‌ടറികളിലെയും ഉള്ളടക്കങ്ങൾ കാണാൻ:  
  ```commandline
  ls -R
  ```  

## ഡയറക്‌ടറികൾ സൃഷ്ടിക്കുകയും നീക്കം ചെയ്യുകയും ചെയ്യുക  

- **mkdir** ഉപയോഗിച്ച് പുതിയ ഡയറക്‌ടറി സൃഷ്ടിക്കാൻ:  
  ```commandline
  mkdir thisdirectory
  ```  
- **mkdir -p** ഉപയോഗിച്ച് നെസ്റ്റഡ് (parent/child) ഡയറക്‌ടറികൾ സൃഷ്ടിക്കാൻ:  
  ```commandline
  mkdir -p thisdirectory/subdirectory
  ```  
- **rmdir** ഉപയോഗിച്ച് ഒരു ശൂന്യമായ ഡയറക്‌ടറി നീക്കം ചെയ്യാം:  
  ```commandline
  rmdir thisdirectory
  ```  

## ഫയലുകളും ഡയറക്‌ടറികളും മാറ്റുന്നതിനും പുനർനാമകരണം ചെയ്യുന്നതിനും  

- **mv** ഉപയോഗിച്ച് ഫയലുകൾ അല്ലെങ്കിൽ ഡയറക്‌ടറികൾ മാറ്റാം:  
  ```commandline
  mv thisdirectory newdirectoryname
  ```  
- ഫയൽ അല്ലെങ്കിൽ ഡയറക്‌ടറി പുനർനാമകരണം ചെയ്യാൻ:  
  ```commandline
  mv olddirectory newdirectory
  ```  

## ഫയലുകൾ സൃഷ്ടിക്കുകയും നീക്കം ചെയ്യുകയും ചെയ്യുക  

- പുതിയ ഫയൽ സൃഷ്ടിക്കാൻ **touch** കമാൻഡ് ഉപയോഗിക്കുക:  
  ```commandline
  touch new_file_name
  ```  
- ഒരു ഡയറക്‌ടറിയിലൊരു ഫയൽ സൃഷ്ടിക്കാൻ:  
  ```commandline
  touch directory/new_file_name
  ```  
- **rm** ഉപയോഗിച്ച് ഫയലുകൾ നീക്കം ചെയ്യാൻ:  
  ```commandline
  rm file_name
  ```  
- ഡയറക്‌ടറികൾ ഉൾപ്പെടെ മുഴുവനായി നീക്കം ചെയ്യാൻ:  
  ```commandline
  rm -r directory_name
  ```  
- പ്രായോഗികമായി ഇല്ലാത്ത ഫയലുകൾക്കായി മുന്നറിയിപ്പ് നൽകാതെ നീക്കം ചെയ്യാൻ:  
  ```commandline
  rm -f file_name
  ```  
- നീക്കം ചെയ്യുന്ന പ്രക്രിയ പരിശോധിക്കാനായി:  
  ```commandline
  rm -v file_name
  ```  
- ഒരു ഡയറക്‌ടറിയിലെ എല്ലാ ഫയലുകളും നീക്കം ചെയ്യാൻ:  
  ```commandline
  rm *
  ```  

## ഉപസംഹാരം  

BASH ടെർമിനലും Git-ഉം ഒരുമിച്ച് ഉപയോഗിക്കുന്നത് പ്രോഗ്രാമർമാർക്ക് ഏറ്റവും മികച്ച വേർഷൻ കൺട്രോൾ സംവിധാനവും ഫയൽ മാനേജ്മെന്റും നൽകുന്നു. **mkdir, rmdir, rm, mv, cd, ls, pwd** എന്നിവയും, Git-നു വേണ്ട **git init, git add, git commit, git push, git pull** തുടങ്ങിയ കമാൻഡുകളും പരിചയപ്പെടുന്നത് വളരെ പ്രധാനമാണ്. കൂടുതൽ പ്രാക്ടീസ് ചെയ്യുന്നതോടെ ഈ കമാൻഡുകൾ എളുപ്പത്തിൽ മനസ്സിലാക്കാനും, നിങ്ങളുടെ ഡെവലപ്പ്മെന്റ് പ്രവൃത്തി പ്രവഹനം മെച്ചപ്പെടുത്താനും കഴിയും.  
