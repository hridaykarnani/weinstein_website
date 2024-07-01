README
How to edit a page (general):
    In the folder containing the webpage, select the page you wish to edit, and open it using notepad, Visual Studio Code, or any other text or code editor
    index.htm --> Homepage
    research.htm --> Research page
    teaching.htm --> Teaching page
    links.htm --> Links page
    styles.css --> style editor (caution, affects all pages)
    Make sure to save the .htm after you edit

How to change the profile picture:
    Upload desired image to folder as a jpg
    Go to index.htm and find 
    <div class = "image-container">
		<img src="profile.jpg" alt="David Weinstein">
	</div>
    Replace "profile.jpg" with your new image. 
    Alternatively, you can simply delete the old image and name your new image profile.jpg 

How to edit the homepage text:
    Go to index.htm and find the text you are trying to edit
    Ex: 
    <div class = "text">
		<p> <strong> Welcome</strong></p>
      	<p> David E. Weinstein is the Carl S. Shoup Professor of the Japanese Economy at Columbia University. He is also the Director of the Center on Japanese Economy and Business, Director of the Japan Project at the National Bureau of Economic Research, and a member of the Federal Economic Statistics Advisory Committee.</p>
	</div>
    Replace or edit the text between the <> objects
    Ex:
    <div class = "text">
		<p> <strong> Welcome</strong></p>
      	<p> Welcome to the New Text</p>
	</div>

How to edit contact info:
    Find this object:
    <div class = "flex-container">
	    <div = "texty">
		    <p><strong>Contact</strong></p>
		    <p><strong>Email:</strong> dew35@columbia.edu</p>
		    <p><strong>Phone:</strong> (212) 854-5524</p>
		    <p><strong>Office:</strong> 1130A International Affairs Building</p>
		    <p><strong>Mailing Address:</strong></p>
		    <p>Economics Department</p>
		    <p>Columbia University</p>
		    <p>420 W 118th St, MC 3308 </p>
		    <p>New York, NY 10027</p>
	    </div>
    </div>
    Make the required changes to the text without altering the <p> or </p> symbols

How to add a new paper to the research page:
    go to the research.htm page
    Upload pdfs of the paper and appendix (if available) and/or an image of a graph (as a jpg)
    Here is a sample template
    <div class = "citation">
        <w><a href="Your_Paper_Here.pdf" target="_blank">The Paper Title</a></w>
	    <p> Your Coauthors</p>
	    <p><a href = "Your_Appendix_Here.pdf" target="_blank">Appendix</a></p>
        <li><details><summary>Abstract</summary><p>Your Abstract Here.</p></details></li>
        <li><details><summary>Selected Media</summary><img src="Your_Image_here.jpg" alt="results"></details></li>
    </div>
    Replace the text and links with the links you want to use, and copy-paste the template into the index.htm before or after any other citation. 

How to change the text on the Teaching page:
    go to teaching.htm and find this object
    <section id="teaching">
      <h2>Fall 2023 Courses</h2>
      <p>ECON GU4325: Economic Development of Japan</p>
      
      <!-- Add more teaching details as needed -->
    </section>
    Change the text as desired. If you want to add more lines, use this template and paste it below the appropriate text:
    <p> Your Text Here <p>

How to add a link to the Links page:
    go to links.htm page
    Use this template:
    <p><a href = "Your Link">Your Link's Title</a></p>
    Copy paste after any other link

