This project is designed for personalizing audiogram for firefighters - the ones who are working in the noisy environments.
The components needed in the project are: Teensy board, NFC module (PN532), LED screen (for debugging purpose).

Project Skeleton Files:
1. debug: for debug the functionality of the device such as NFC reading, NFC writting, I2C detection
2. src: contains the source file of device such as writer, reader, mobile phone app (for communicating between Otos and Savox)
3. index.html: simple website for transfering hearing profile (XML format) to writer then NFC cards
4. requirements: requirements from stakeholder such as Savox or Otos
5. dataset: contains hearing profile from real life measurement
6. log.txt: diary about the project's progress
