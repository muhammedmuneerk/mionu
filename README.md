# mionu
[v0 dev | muhammedmuneerk15](https://v0.dev/chat/8gl9U5DYeSm)
[chatgpt | muhammedmuneerk15 | image generating prompts](https://chatgpt.com/share/67673089-172c-800f-8f52-bccbb33f881d)



for circle animation the image fixes perfectly inside the crcle in this codesnippet
--------------------
                    |
                    V
-------------------> HTML------>
                                |
                                |
                                V
 <div class="skill-item" data-skill="85">
                        <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
                            <!-- Outer Circle -->
                            <circle cx="50" cy="50" r="45" stroke="gray" stroke-width="5" fill="none" />
                            
                            <!-- Clip Path for the Image -->
                            <defs>
                                <clipPath id="circle-clip">
                                    <circle cx="50" cy="50" r="45" />
                                </clipPath>
                            </defs>
                            
                            <!-- Image Inside the Circle -->
                            <image href="./images/icons/Beverage Service-bw-bgremoved.png" 
                                   x="15" y="5" 
                                   width="90" height="90" 
                                   clip-path="url(#circle-clip)" />
                            
                            <!-- Progress Circle -->
                            <circle cx="50" cy="50" r="45" class="progress" stroke="blue" stroke-width="5" fill="none" />
                        </svg>
                        <span class="skill-name">Beverage Service</span>
                    </div>

                --------- CSS FOR THE HTML ABOVE---->
                                                    |
                                                    V
                ---CSS---
                    |
                    |
                    |
                    |
                    |
                    V

                    /* ------------------- */
/* .skill-item .progress "with the circle animations" */
/* .progress {
    stroke: var(--secondary-color);
    stroke-dasharray: 283; 
    stroke-dashoffset: 283; 
    transition: stroke-dashoffset 0.3s ease-in-out;
}

.skill-item:hover .progress {
    stroke-dashoffset: 0; 
}

.skill-item {
    stroke: var(--secondary-color);
    stroke-dasharray: 283;
    stroke-dashoffset: 283;
    transition: stroke-dashoffset 1s ease-in-out;
} */
/* ----------------------------- */