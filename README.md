This repository contains all the Kubernetes documentation in PDF format.

How the files are structured?

PDF files can be found under PDFs directory; they are grouped in sections:

Setup (Getting Started)

Concepts

Tasks

Tutorials

Reference

kubectl Reference




For a more detailed index, see here

Dependencies

docker

python3

pipenv

requests-html



How to run the code

Install the dependencies. Use $ pipenv install for installing python packages.

$ pipenv shell

$ python kubernetes-doc.py

$ ./gen_ref_docs.sh



Troubleshooting

If weasyprint is stuck when generating pages, check if you run out of memory, generating the larger PDFs (e.g. Reference.pdf) is quite memory heavy.
