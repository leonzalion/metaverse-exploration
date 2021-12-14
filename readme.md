# Metaverse Exploration

I'm by no means an expert on the subject, but I want to explore/experiment with an idea I have for the Metaverse: right now, all the computation and load is handled client-side. The client needs powerful CPUs and GPUs to render everything, and it's really difficult to fit that powerful technology onto a small area like AR glasses. In addition, the Metaverse will inevitably expand to thousands to hundreds of thousands of concurrent users all in one place (e.g. an extremely large concert or something), so these tiny CPUs and GPUs will inevitably reach a limit at some point.

What if we moved all this necessary computational power over to the server-side? The client would just send the server certain actions/movements, and then the server would apply these actions/movements to some scene and then send an image back to the client of what they're viewing. Send images fast enough and it becomes a video, so all the client-side would need to optimize is the rendering and displaying of videos, and this scales very well in a scenario where there's much more activity, such as a large concert, as it's much easier to scale server infrastructure since it's not limited by the same size constraint as the client-side technology.

Of course, there are many issues with this approach, such as the need for high data-transfer and extremely-low latency to make the client feel like they are moving in real-time. As a non-expert in these subjects, I don't know how difficult it is to achieve extremely-low latency, but I do know that we've already scaled high data-transfer when it comes to videos: just look at YouTube, which needs to send massive amounts of data to millions of concurrent users! I'm hoping to do some more research and experiments into this area (when I get the time), but for now I thought I'd just share this idea with people who know more about the subject than I do to let me know of the problems with moving all the computation server-side instead of client-side.

