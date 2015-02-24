# Send-A-Kitten
Have you ever wanted to send someone a kitten of a picture but didn't want to leave your terminal? Well now you don't have to!

# Requirements
**Send-A-Kitten** requires a local SMTP server to be running

# Installation
To install simply clone this repository using `git clone https://github.com/jturner30/send-a-kitten.git`. You can also make an alias to it using `echo "alias send_a_kitten=<directory where you cloned the repo>/send_a_kitten >> ~/.bashrc` (change to `~/.zshrc for zsh)

# Usage
## Sending a random cat picture
`send_a_kitten to_email@domain.com from_email@domain.com`
## Sending a random cat picture with your name attached
`send_a_kitten -n YOUR_NAME to_email@domain.com from_email@domain.com`
## Sending a random cat picture with a nice message attached
`send_a_kitten -m "YOUR MESSAGE" to_email@domain.com from_email@domain.com`

# Attribution
This program relies on the wonderful **Cat API** to grab its images. Show them some love at http://thecatapi.com

