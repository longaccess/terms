Security Overview

Last Modified: April 29, 2014

We provide this overview so that you can better understand the
security measures we’ve put in place to protect the information that
you store using Long Access.

Secure Storage

We encrypt the files that you store on Long Access using the AES-256
standard, which is the same encryption standard used by banks to
secure customer data. Encryption for storage is applied BEFORE files
are uploaded, and we DO NOT manage the encryption keys. In fact at
such point in time you are the only holder of such encryption keys.

Long Access uses Amazon S3 for data storage. Amazon stores data over
several large-scale data centers. According to Amazon, they use
military grade perimeter control berms, video surveillance, and
professional security staff to keep their data centers physically
secure.

You can find more information about Amazon's security at the Amazon
Web Services' website.

Amazon and Long Access also employ significant protection against
network security issues such as Distributed Denial of Service (DDoS)
attacks, Man in the Middle (MITM) attacks, and packet sniffing.

Secure Transfers

Your files are sent between Long Access’s desktop clients and our
servers or Amazon’s Services such as Amazon S3 and Amazon Glacier
over a secure channel using 256-bit SSL (Secure Sockets Layer)
encryption, the standard for secure Internet network connections.

Your files are sent between Long Access’s mobile apps and our servers
over a secure channel using 256-bit SSL encryption where supported.
Not all mobile media players support encrypted streaming, so media
files streamed from our servers are not always encrypted.

Data Durability and Reliability

Amazon keeps redundant backups of all data over multiple locations to
prevent the remote possibility of data loss. Specifically:

Amazon S3 provides a highly durable storage infrastructure designed
for mission-critical and primary data storage. The service
redundantly stores data in multiple facilities and on multiple
devices within each facility. To increase durability, Amazon S3
synchronously stores your data across multiple facilities before
returning SUCCESS. In addition, Amazon S3 calculates checksums on all
network traffic to detect corruption of data packets when storing or
retrieving data. Unlike traditional systems which can require
laborious data verification and manual repair, Amazon S3 performs
regular, systematic data integrity checks and is built to be
automatically self-healing.

Amazon S3’s standard storage is:

- Backed with the Amazon S3 Service Level Agreement.
- Designed for 99.999999999% durability and 99.99% availability of
objects over a given year.
- Designed to sustain the concurrent loss of data in two facilities.

The above statement is available at
http://aws.amazon.com/s3/#protecting.

Privacy

We guard your privacy to the best of our ability and work hard to
protect your information from unauthorized access.

Long Access has no technical means of viewing your data, encrypted in
your Archives. In addition, Long Access employees are prohibited from
viewing the content of files you store in your Long Access account,
and are only permitted to view file metadata (e.g., archive names and
upload dates). In addition, we employ a number of physical and
electronic security measures to protect user information from
unauthorized access.

Third-party Applications

If you choose to access Long Access using third-party applications
(“apps”), be aware that those apps utilize their own security
protocols and have their own privacy policies. If you’re not
comfortable with the privacy and security features of those apps, you
shouldn’t use them to access Long Access. For example, third-party
apps might not employ encryption when transmitting data, might
collect information that Long Access does not, and might use
information differently than Long Access does.

Compliance with Laws and Law Enforcement

As set forth in our privacy policy, and in compliance with Greek law,
Long Access shall cooperate with Greek judicial authorities when it
receives valid legal process, which may require Long Access to
provide the access to your archives.

I think I've found a security exploit. Where do I report security
concerns?

We take a number of measures to ensure that the data you store on
Long Access is safe and secure. While we're very confident in our
technology, we recognize that no system can guarantee data security
with 100% certainty. For that reason, we will continue to innovate to
make sure that our security measures are state of the art, and we
will investigate any and all reported security issues concerning Long
Access's services or software. For a direct line to our security
experts, report security issues to security@longaccess.com.

We'll fully credit anybody whose reports lead to the improvement of
Long Access security. A list of those who have contributed reports
leading to a bug or security issue can be found on our special thanks
page.
