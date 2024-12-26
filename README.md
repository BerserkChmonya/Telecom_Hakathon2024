# Telecom_Hakathon2024

![Main Page](images/photo_3_2024-12-26_16-41-54.jpg "Main page")

![Main Page](images/photo_1_2024-12-26_16-41-54.jpg "Main page")

# Tech Stack

<div align="center">
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/202896760-337261ed-ee92-4979-84c4-d4b829c7355d.png" alt="Tailwind CSS" title="Tailwind CSS"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/117447155-6a868a00-af3d-11eb-9cfe-245df15c9f3f.png" alt="JavaScript" title="JavaScript"/></code>
	<code><img width="50" src="https://github.com/marwin1991/profile-technology-icons/assets/136815194/e56b5093-2f58-40cc-b194-5bdde41077b5" alt="Svelte" title="Svelte"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/117201156-9a724800-adec-11eb-9a9d-3cd0f67da4bc.png" alt="Java" title="Java"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/183423507-c056a6f9-1ba8-4312-a350-19bcbc5a8697.png" alt="Python" title="Python"/></code>
</div>


# Inspiration

Our main inspiration comes from being cybersecurity students eager to gain hands-on experience in our field of study. Despite our theoretical knowledge, we had never had the opportunity to apply it in practice, and we thought, "If not now, during our bachelor's year, then when?" This project gave us the perfect chance to bridge that gap.

We also firmly believe that projects like this are essential for the development of secure web applications. Vulnerabilities are a real and constant threat, and the number of people who seek to exploit them is significant. Addressing these risks proactively is not just a learning opportunity but also a necessity for creating a safer digital environment.

# What It Does

Our web application takes three inputs:

1. A link to the web page.
2. A link to the respective GitHub repository for the page.
3. A `.csv` file containing a list of vulnerabilities related to the page.

   ![Input Visualisation](images/photo_5_2024-12-26_16-41-54.jpg "Input Visualisation")

In the background, the application tests which vulnerabilities are exploitable. As output, it displays:

- The exploitable vulnerabilities.
- A short description of each vulnerability.
- The location in the code causing the vulnerability.
- Recommended mitigation steps.

  ![Output Visualisation](images/photo_4_2024-12-26_16-41-54.jpg "Output Visualisation")

# How We Built It

To build the application, we used several server-side programming languages, frameworks, and a trained OpenAI model. The components include:

- **Front-end**: Built using _SvelteKit_ and _Tailwind CSS_.
- **Back-end**: Developed using _Java_.
- **Vulnerability Testing**: A _Python script_ checks if the provided vulnerabilities are exploitable.
- **OpenAI Model**: Simulates attacks and formats the output into a human-readable form.

# Figma Board
Presentation for our work available here : [Figma](https://www.figma.com/design/wFmSR4CkxYzdcbI2x4a6ts/WebWard?node-id=0-1&t=afJ5xMjNSjtoF9WN-1)

# Challenges We Ran Into

The main challenge for us was determining whether a vulnerability is truly exploitable. Having never worked on a similar task before, we were initially unsure about the algorithms and methods needed to achieve this goal. Our knowledge was limited to theoretical concepts, making it difficult to apply them in practice. Overcoming this hurdle required extensive research, experimentation, and learning, which eventually helped us develop a functional approach despite our initial inexperience.

# Accomplishments That We're Proud Of

While our application is not perfect, we take great pride in both our idea and the effort we’ve put into creating a user-friendly and visually appealing front end. The design of our interface is intuitive and engaging, ensuring that users can easily interact with the application. We’re confident that our idea has the potential to make a meaningful impact in the realm of vulnerability testing and mitigation.

# What We Learned

This project taught us a great deal about:

- Penetration testing.
- Various types of vulnerabilities and how they can be exploited.
- The practical aspects of identifying security flaws and understanding their potential impact.

We also realized the importance of teamwork. Effective collaboration, communication, and shared effort are essential for overcoming challenges and successfully completing complex tasks under time pressure.

# What's Next for WebWard

Our solution is not perfect, and we recognize there is room for improvement. The next steps in the project’s development include:

1. Strengthening the back-end performance and reliability by:
   - Implementing a more robust algorithm for processing `.csv` files efficiently and accurately.
   - Refining the detection of exploitable vulnerabilities to ensure higher precision.
2. Further developing the OpenAI model to produce even more accurate and relevant outputs for vulnerability descriptions and mitigation steps.

