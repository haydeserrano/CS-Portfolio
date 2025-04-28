# CS-Portfolio
## Course Reflection

**1. Who was the client?**  
The Gaming Room, a startup wanting to expand their Android‐only game “Draw It or Lose It” to other platforms.

**2. What did you do well?**  
I organized the design document clearly, used diagrams to explain architecture, and aligned everything to the rubric.

**3. How did the design doc help your code?**  
Having a detailed API spec and data model upfront meant my Dropwizard server code matched the client’s needs with no rework.

**4. What would you revise?**  
I’d refine the security section to include token-based auth rather than just BasicAuth, to show a more modern best practice.

**5. How did you interpret user needs?**  
By keeping “rapid image rendering” front and center, I chose architectures (caching, container limits) that ensure smooth gameplay.

**6. Future design approach?**  
I’ll sketch high-level workflows first, then break them into microservices and data contracts—this keeps the design modular and testable.
