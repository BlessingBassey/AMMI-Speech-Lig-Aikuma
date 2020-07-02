# AMMI-Speech-Lig-Aikuma
AMMI course on Speech Recognition, given by Gabriel Synnaeve, Neil Zeghidour, Laurent Besacier and Emmanuel Dupoux.

### The APP:

The lig-aikuma app has so many versions, all were tried on my andriod phone but unfortunately none was working or compatible with my phone, so I was left with no other choice than to use the android studio with the Lig-Aon my computer system. 

### The Tutorial:

The tutorial consist of the Mercer Mayer wordless picture book of 1969 Frog (saved as frog story file), the image-by-image version of the book. The speach elicitation by image was done in the Nigerian Pidgin. The short speech were then concatenated using the online tools and afterwards converted to .wav file. The the Translating of the elicitated speech was done using the ibibio language. These two languages are from the western and southen part of Nigeria respectively. 

### The Project:

Data were collected from the Jehovah Witness Church online using this link https://www.jw.org/pcm/wetin-we-get/different-different-book/jesus/preaching-work-galilee/sermon-on-the-mount/

The data was about the Bible stories. Elicitation by text were made in the Ibibio language. I segmented the data into chunks of like 10-15 words per sentence, and I had up to 50-57 sentences making up a section, and over all I have 20 sections. The the folder, there is a notebook called Nigerian_Pidgin_preprocessing.ipynb , The notebook was used to do some data preprocessing. In there, I calculated hours of speech I recorded, filtered out the corrupted files, Organized the data by matching the recoding to it corresponding label text file using the linkers in each of the sections. Afterwards, I splited the data into train test and validation set, and also have the data/charset.txt file which shows the different characters
