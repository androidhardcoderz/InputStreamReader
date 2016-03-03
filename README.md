# InputStreamConverter
Android / Java class that accepts an InputStream as parameter and returns a full string values of contents
Useful for JSON types streams, XML streams before parsing the contents

## Installation
Add class defintion to your Java project: 
## Usage
Create a new InputStreamReader object by 2 ways

InputStreamConverter inputStreamConverter = new InputStreamConverter(context);
inputSteamConverter.convertInputStream("open inputstream");
    or
new InputStreamConverter(context).convertInputStreamToString(open inputstream);

<b>Context</b> - the activity context for the application or activity;
    calling from inside fragment use getActivity();
    calling from inside Activity use this or YourActivityName.this
    calling from inside Widget Class(ex. class extends LinearLayout) use getContext();
    
<b>Method Parameter</b>
  InputStream - BufferedInputStream, FileInputStream any subclass of InputStream

