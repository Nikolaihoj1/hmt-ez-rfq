# hmt-ez-rfq


HMT ez-q

i want to make a python app with a user interface - webbased for now

The app is going to be an app to make quoting for manufactoring better and easier.

Functions:


importing RFQ pdf or manually putting in the RFQ parts in a list with part number, part name, quantity, files (step file and pdf) and with file preview both of file types is needed in the app. 


for each part we need to be able to put in a list of operations:
	1. starts with 1 operation but you should be able to add more if required.
	2. process selection: (needs to be database driven - and you should be able to add more processes here - for now we just start with the following: milling 3axis, milling 5 axis, turning, welding, grinding, manual labor, external)
	3. process time: you should be able to select hours:minutes for each process - there needs to be setup time, programming, first part time, part time production (if its external we need to put in how many days this external process will take and what it will cost.) all times, process times should be selected from a dropdown menu with hours:minutes (5 min steps)
	4. material cost price: material cost price will be pr part for now and will be manually put in a text field (in the future we will be automating this more)
    5. part price will be calculated live and will be calculated this way - first part is setup time, programming and first part time + (material * markup). remaining parts are part time production + (material * markup).
    6. a part descrption where extra info can be put will be avalible also. 
    7. all quotes will be saved to a text database for future reviewing - should be accessable from a send quotes menu and editable by loading it again.
    6. old quotes should be able to be used as a new quote by selecting a copy quote to new in the all quotes menu. 

The quote will be exported on a nicely presented pdf file with client info in top left and sender info in top right. and below is a list with part number, part name, part description and part price. 

Incase of a PO is send for the quoted parts we need to be able to make a nicely presented pdf with a page for each part - the pdf contains the process routing with all the processes and process times. 

App needs to have a simple and nicely user interface for easy use. 
