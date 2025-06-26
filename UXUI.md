<div class="project-card">
  <div class="project-flex-container">
    <div class="project-image-column">
      <img src="{{ '/Images/py3img2.png' | relative_url }}" alt="First-person view of the diegetic UI on a tablet">
      </div>
    <div class="project-text-column">
      <h3>Project: Diegetic UI Prototype</h3>
      <div class="project-meta">
        <ul>
          <li><strong>Duration:</strong> 4 Days</li>
          <li><strong>Team Size:</strong> Solo Project</li>
          <li><strong>My Roles:</strong> UI/UX Designer, Systems Designer</li>
        </ul>
      </div>
      <div class="project-tools-summary">
        <span class="tool-tag"><i class="fa-brands fa-unreal"></i> Unreal Engine</span>
        <span class="tool-tag"><i class="fa-solid fa-diagram-project"></i> Blueprints</span>
      </div>
      <p>This prototype explores the power of diegetic UI to create a more immersive player experience. The goal was to remove traditional on-screen HUD elements and instead integrate all essential information—like navigation, health, and team status—directly onto devices the player character carries and wears in the game world.</p>
    </div>
  </div>
  <div class="project-details-row">
    <details>
      <summary>Read more about the implemented systems</summary>
      <div class="details-content">
        <div class="process-stage">
          <h3>Project Goal & Design Philosophy</h3>
          <div class="stage-description">
            <p>The core philosophy behind this project was to completely eliminate traditional, 'pasted-on' UI. My goal was to prove that all necessary player information could be delivered through in-world objects, strengthening immersion and making the player feel truly present in the game's environment. The challenge was to make this information clear and readable without sacrificing realism.</p>
          </div>
        </div>
        <div class="process-stage">
          <h3>Key Features Implemented</h3>
          <div class="stage-content-flex">
            <div class="stage-gallery">
              <p class="gallery-label">In-game examples:</p>
              <a href="{{ '/Images/WatchPreview.gif' | relative_url }}" target="_blank"><img src="{{ '/Images/WatchPreview.gif' | relative_url }}" alt="The multi-function watch UI" class="gallery-thumbnail"></a>
              <a href="{{ '/Images/PhonePreview.gif' | relative_url }}" target="_blank"><img src="{{ '/Images/PhonePreview.gif' | relative_url }}" alt="The SATCOM tablet menu" class="gallery-thumbnail"></a>
            </div>
            <div class="stage-description">
              <ul>
                <li>
                  <strong>Multi-Function Wristwatch:</strong> I designed and implemented a wristwatch UI worn by the player. Its screen can be toggled between two modes:
                  <br>- <strong>Navigation Mode:</strong> Displays a real-time compass and GPS with objective markers.
                  <br>- <strong>Vitals Mode:</strong> Functions as a heart-rate monitor that serves as a diegetic health bar. The display changes color from green to yellow to red based on health, and flatlines upon death, providing clear at-a-glance feedback.
                </li>
                <li>
                  <strong>"SATCOM" Tablet Menu:</strong> To handle more complex information, I created a handheld tablet that functions as the game's menu system. The player physically raises the device to interact with it. I prototyped the framework for multiple tabs including SATCOM (Map/Objectives), Team Status, a Briefing screen, and a functional Inventory.
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="process-stage">
          <h3>Outcome & Reflection</h3>
          <div class="stage-description">
            <p>The result is a successful proof-of-concept demonstrating how multiple layers of player information can be integrated into the game world. The biggest challenge was balancing the realism of the devices with the need for clear, instantly readable information during gameplay. This project was a valuable exploration into creating immersive player feedback systems.</p>
          </div>
        </div>
      </div>
    </details>
  </div>
</div>
