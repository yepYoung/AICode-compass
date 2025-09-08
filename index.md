---
layout: default
---

<style>
  .hero {
    text-align: center;
    padding: 4rem 2rem;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
  }
  .hero h1 {
    font-size: 3.5rem;
    margin-bottom: 1rem;
    font-weight: bold;
  }
  .hero p {
    font-size: 1.5rem;
    max-width: 600px;
    margin: 0 auto 2rem;
  }
  .hero-image {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
    margin-bottom: 2rem;
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
  }
  .cta-button {
    display: inline-block;
    padding: 1rem 2rem;
    background-color: #ffffff;
    color: #667eea;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    transition: all 0.3s ease;
  }
  .cta-button:hover {
    background-color: #f0f0f0;
    transform: translateY(-2px);
  }
  .features {
    display: flex;
    justify-content: space-around;
    padding: 4rem 2rem;
    flex-wrap: wrap;
  }
  .feature-item {
    text-align: center;
    max-width: 300px;
    margin-bottom: 2rem;
  }
  .feature-item .emoji {
    font-size: 3rem;
  }
  .feature-item h3 {
    font-size: 1.5rem;
    margin-top: 1rem;
    margin-bottom: 0.5rem;
  }
  .survey-section {
    background-color: #f9f9f9;
    padding: 4rem 2rem;
    text-align: center;
  }
  .survey-section h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
  }
  .survey-section p {
    font-size: 1.2rem;
    max-width: 600px;
    margin: 0 auto 2rem;
  }
</style>

<div class="hero">
  <img src="https://images.unsplash.com/photo-1620712943543-290d24270f34?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="AI and Code" class="hero-image">
  <h1>🤖 AICode-compass</h1>
  <p>Navigating the Future of AI-Powered Software Development</p>
  <a href="#about" class="cta-button">Learn More</a>
</div>

<div class="features">
  <div class="feature-item">
    <div class="emoji">🚀</div>
    <h3>For Everyone</h3>
    <p>Whether you're a seasoned developer or new to coding, this guide helps you leverage AI in your projects.</p>
  </div>
  <div class="feature-item">
    <div class="emoji">💡</div>
    <h3>AI as a Co-pilot</h3>
    <p>Understand how to effectively use AI as both a driver and a co-pilot in your development workflow.</p>
  </div>
  <div class="feature-item">
    <div class="emoji">🛠️</div>
    <h3>Tools & Practices</h3>
    <p>Discover the latest tools, models, and best practices in the rapidly evolving world of AI coding.</p>
  </div>
</div>

<div id="about" style="padding: 4rem 2rem;">
  <h2 style="text-align: center; font-size: 2.5rem; margin-bottom: 2rem;">About This Guide</h2>
  <p style="font-size: 1.2rem; max-width: 800px; margin: 0 auto; line-height: 1.6;">
    The way we interact with computers and write code is undergoing a massive transformation. New Large Language Models (LLMs), tools, and coding practices are emerging at a breathtaking pace. This guide is your central hub to navigate this exciting new landscape. We consolidate and simplify the vast amount of information about AI-assisted programming to provide clear, actionable insights. Our goal is to demystify "vibe coding" and empower you to build software products and UI interfaces, even if you've never coded before, and to help experienced programmers integrate AI into their daily work to boost productivity and creativity.
  </p>
</div>

<div class="survey-section">
  <h2>📊 Help Us Improve!</h2>
  <p>We value your feedback. Please take a moment to complete our survey and let us know what you think.</p>
  <a href="{{ site.survey.url }}" target="_blank" class="cta-button">Take the Survey</a>
</div>
