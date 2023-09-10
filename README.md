# Web OTP Preview
Making hands dirty with WebOTP API on modern web browsers


### Format of the message
Special format of message is required to use Web OTP API. The message should satisfy the following conditions:

1. Message can begin with an optional human readable text. For example: Don’t Share your OTP or Never share your OTP or any other relevant text.
2. The Last line of the message consists of two parts. One is the host part and other is the OTP. The host part of the URL of the website that invoked the API must be preceded by ‘@’ sign. The next part is the OTP which should preceded by ‘#’ pound sign. For example: @webotp-api-preview.s3.eu-north-1.amazonaws.com #9999

### Further Reading:

https://developer.chrome.com/en/articles/web-otp/
