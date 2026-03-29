# Ziggy and the Book                                                                                                                                     
   
  An interactive illustrated children's story where text reflows in real time around a animated caterpillar, built with                                    
  [pretext](https://github.com/chenglou/pretext).                                                                                                        
                                                                                                                                                           
  ## How it works                                                                                                                                        

  Move your mouse to guide Ziggy across the page - the story text wraps around him as he moves, using pretext's `layoutNextLine` API to measure and fit    
  each line into the available space around his body. Click to release butterflies.
                                                                                                                                                           
  ## Built with                                                                                                                                          

  - **[pretext](https://github.com/chenglou/pretext)** by [chenglou](https://github.com/chenglou) — fast, accurate text measurement and layout without DOM 
  reflow. The entire text-wrapping effect is driven by two pretext calls: `prepareWithSegments()` (once) and `layoutNextLine()` (every frame, per column).
  - Canvas 2D for all rendering                                                                                                                            
                                                                                                                                                           
  ## Live demo
                                                                                                                                                           
  [smarkstrife.github.io/ziggy-demo](https://smarkstrife.github.io/ziggy-demo)
