# Website Login Traffic Analysis

## Challenge Description
A company reported an unauthorized login to its internal web portal.  
The only evidence available was a network capture file (`.pcap`).  
The login page was still active, and the flag was hidden behind successful authentication.

**Hint:**

> “Not all packets are noise. Some talk too much.”

---

## Analysis / Approach
At first, I reviewed the provided files to understand the challenge scenario. The login page itself did not reveal any immediate clues or flags, so the focus shifted to the network capture file.

I opened the `.pcap` file using Wireshark and applied filters to isolate HTTP traffic. After filtering the packets, I identified a `POST` request sent to the `/login` endpoint. By following the HTTP stream, I was able to reconstruct the complete request and inspect the transmitted data.

The login credentials were sent in plain text as part of the HTTP POST body. This allowed the username and password to be extracted directly from the network traffic. Using the recovered credentials, I logged into the web application and accessed the protected page, where the flag was displayed.

---

## Tools
- Wireshark
- Web browser

---

## Filters / Techniques Used
http
http.request.method == "POST"
Follow → HTTP Stream
