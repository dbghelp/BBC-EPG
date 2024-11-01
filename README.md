# BBC-EPG

## Overview

This repository contains the XML EPG (Electronic Program Guide) for BBC TV channels. The EPG provides a schedule of the current and upcoming TV programs, enabling users to easily see what's on and plan their viewing.

Preview: https://dbghelp.github.io/epg.html?file=https://raw.githubusercontent.com/dbghelp/BBC-EPG/refs/heads/main/bbc.xml

## Features

- XML formatted EPG for BBC channels
- Up-to-date information on channel programming
- Easy integration with various applications and services

## Usage

To use the EPG data, you can fetch the XML file from this repository and parse it in your application to display the program schedule.

In your M3U8 playlist, 

1. Change your url-tvg to "https://raw.githubusercontent.com/dbghelp/BBC-EPG/refs/heads/main/bbc.xml":

```#EXTM3U url-tvg="https://raw.githubusercontent.com/dbghelp/BBC-EPG/refs/heads/main/bbc.xml" refresh="3600"```

2. Change your tvg-id to the following for the respective channels:
  
| tvg-id        | Channel Name   |
|---------------|----------------|
| bbcone        | BBC One        |
| bbctwo        | BBC Two        |
| bbcthree      | BBC Three      |
| bbcfour       | BBC Four       |
| cbbc          | CBBC           |
| cbeebies      | CBeebies       |
| bbcscotland   | BBC Scotland   |
| bbcnews       | BBC News       |
| bbcparliament | BBC Parliament |
| bbcalba       | BBC Alba       |
| s4c           | S4C            |
