<h1 align="left">:computer: VSCODE configuration for C, C++ compilation </h1>

## Introduction

Step-by-step how to install and configure VSCODE to compile in C, C++

## Environment Setup

**Prerequisites:**
* Installing <a href="https://code.visualstudio.com">VSCODE</a>
* Installing <a href="https://sourceforge.net/projects/mingw/">MINGW</a>

## VSCODE

When you finish the VSCODE installation open the extensions tab (Ctrl + Shift + X).
<p align="left">
  <img src="https://user-images.githubusercontent.com/105325980/168409638-6eef1444-0b6a-4f70-9f18-2174be7c7eef.png" />
</p>

**Learn more about extensions:**
* <a href="https://docs.microsoft.com/pt-br/cpp/build/reference/microsoft-extensions-to-c-and-cpp?view=msvc-170">C/C++</a>

### <img align="left" alt="Note" width="22px" src="https://cdn-icons.flaticon.com/png/512/5515/premium/5515161.png?token=exp=1652560222~hmac=eeebe534247b3fa290e4ee2aac52cb24" />Additional note
Running the code without MINGW, open CMD;

✔️ Opening the path to the .c file folder
<p align="left">
  <img src="https://user-images.githubusercontent.com/105325980/168446781-5159b833-b60c-4f71-bb88-555207eded2a.png" />
</p>

<p align="left">
  <img src="https://user-images.githubusercontent.com/105325980/168446839-2426aab7-8141-40f4-95af-1af7dbbcb29d.png" />
</p>

✔️ Transform the file from .c to .exe
<p align="left">
<img src="https://user-images.githubusercontent.com/105325980/168446919-bd0e3920-a9ba-4caa-8914-661e6a96d2cf.png" />
</p>

✔️ Running the .exe file
<p align="left">
<img src="https://user-images.githubusercontent.com/105325980/168446959-4a8dd97c-208a-4f35-9f1d-42be5593a061.png" />
</p>

## MINGW

To compile the codes directly from VSCODE, MINGW must be installed and configured. 

📌 <b> Step one </b>
* Open MINGW Installation Manager

<p align="left">
  <img src="https://user-images.githubusercontent.com/105325980/168445678-430bd301-7e26-4898-9a6b-efafdb04e6f9.png" />
</p>

📌 <b>Step two </b>

<i>Click on the options check box:</i>

* mingw32-base
* mingw32-gcc-g++

Open "Installation", click on "Apply Changes"

📌 <b>Step three </b>
 
Open "System properties", click on "Advanced", click on "environmental variables"
<p align="left">
  <img src="https://user-images.githubusercontent.com/105325980/168446137-8ab818a5-a0fc-44fb-af1a-02da985fef25.png" />
</p>

📌 <b>Step four </b>

Click on "Path", click on "Edit..."
<p align="left">
  <img src="https://user-images.githubusercontent.com/105325980/168446194-5c7b74ce-0fc0-4c33-a610-0d29c144b5da.png" />
</p>

📌 <b>Step five </b>

Click on "New", put the address "E:\MinGW\bin";

Note: E:\MinGW\bin ("E:\MinGW\" = Path of the MinGW installation folder, change if on another disk)

<p align="left">
  <img src="https://user-images.githubusercontent.com/105325980/168446262-4484acd3-6d18-40b3-bde8-703b8f4a0c7d.png" />
</p>

<b>⚠️ Press all OK and restart `VSCODE` </b>

✔️ Finished

## Author
<a target="_blank" href="https://github.com/FNNTHALYS">👤 Thalyson Luan </a>

<a target="_blank" href="mailto:fnnthalys@gmail.com">
  <img align="left" alt="Gmail" width="80px" src="https://ssl.gstatic.com/ui/v1/icons/mail/rfr/logo_gmail_lockup_default_1x_r2.png" />
</a>
