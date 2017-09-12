To decrypt on Unix based system: 

gpg SystemC_Project.tgz.gpg

This will promp you to enter the passphrase.

Source Code for the Multiplexer and Demuliplexer can be found in the Mux-Demux folder. 

Useage:
 
./multiplex mux.wav file1.wav file2.wav file3.wav

Where mux.wav is the resulting file containing all information from file1.wav through file3.wav.

./demultiplex mux.wav FILE1.wav FILE2.wav FILE3.wav

Where mux.wav is the previously multiplexed file and FILE1.wav FILE2.wav and FILE3.wav are the demultiplex signals. 

An example of mux.wav, FILE1.wav, FILE2.wav, FILE3.wav can be found in publicTest folder along with the script used to test these files. 

Note: When the demultipled signals are compared to their orgional values using a array comparison program mean square error between the demultiplex and origional values is less than 10^-5.  
