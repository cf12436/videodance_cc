# Seedance 2.0 China Website Guide: Complete Video Creation Experience from Prompts to Long Videos

I've been using Seedance 2.0 to create videos lately. From initial failures to now being able to generate relatively stable results, I've hit plenty of roadblocks but also gained some useful experience. I'm writing this to share what I've learned over this period for anyone who might find it helpful.

For those looking for a reliable Seedance 2.0 China website with easy access, I recommend trying: [videodance.cc](https://videodance.cc)

## What is Seedance 2.0

Seedance 2.0 is an AI video generation tool launched by ByteDance. Its core capability is generating 4-15 second video clips through text prompts. Beyond pure text, you can also upload images, videos, and audio as references, allowing the AI to generate content based on the materials you provide.

It has solid Chinese language support, which is quite friendly for domestic users. Additionally, the generated videos come with built-in sound effects, so if you don't need custom audio, you can skip the post-production audio work.

Some practical features worth noting:

You can upload up to 9 images, 3 videos, and 3 audio files simultaneously as reference materials. Use images to define character appearance, videos to define movements and camera work, and audio to define rhythm. This multimodal reference approach significantly improves the controllability of the results.

The understanding of Chinese prompts is quite accurate. Whether it's everyday language or professional camera terminology, the recognition rate is pretty good.

Camera movements are fairly natural. Simply adding a few camera movement keywords can generate smooth footage without obvious stuttering or jumping.

Character consistency control is decent. If you use the right methods, you can maintain the same appearance, clothing, and hairstyle across multiple video segments.

The barrier to entry is low. Both mobile and desktop are supported, and if it's your first time, following the tutorial for about ten minutes should get you started.

## How to Write Prompts

Many people's unsatisfactory results mainly stem from poorly written prompts. Either too much scattered information or missing key details means the AI doesn't know what you want.

I've summarized a basic prompt structure. Following this framework to fill in content should prevent the results from deviating too much:

**Duration + Aspect Ratio + Quality Requirements + Subject Description + Continuous Actions + Scene Environment + Lighting & Color Tone + Camera Movement + Visual Style + Anti-Collapse Constraints**

Here's how to write each part:

**Duration and Aspect Ratio**

Place this at the beginning to establish basic parameters first. For example: 15 seconds, 9:16 vertical / 10 seconds, 16:9 horizontal / 8 seconds, 1:1 square.

**Quality Requirements**

No need to write complex terms, a few fixed keywords are enough: 4K ultra-high definition, 2K quality, 1080P HD, cinematic texture, rich details, smooth footage without stuttering, no flashing or ghosting.

**Subject Description**

This is the core of the entire prompt. Be clear about who the main character in the frame is, what they look like, what they're wearing, and what features they have. Don't use vague descriptions like "a good-looking woman."

For example: A 20-year-old East Asian young woman with long straight black hair, gentle smile, wearing a white cotton linen dress, with clear and proper facial features.

**Continuous Actions**

Don't just write "dancing" or "walking," write specific, continuous, slow actions. The more specific, the smoother the generated footage.

For example: An orange kitten slowly strolls across the park lawn, pauses to lean down and smell a flower, then gently swishes its tail before continuing its leisurely walk, movements flowing naturally.

**Scene Environment and Lighting & Color Tone**

Be clear about where the subject is, what time it is, what the lighting is like, and what the overall color tone is.

For example: Beach at sunset, golden evening sun casting on the sea surface, warm orange tones, gentle breeze blowing.

**Camera Movement**

This part has a significant impact on visual quality. Simply adding a few camera movement keywords can noticeably enhance the result.

For example: Medium shot, camera slowly pushes in, smooth tracking / Wide shot, 360-degree steady circular movement / Close-up, fixed camera, background blur.

**Visual Style**

Be clear about the style you want, so the AI won't improvise. For example: Healing and fresh, ancient Chinese style, cyberpunk, vintage film, etc.

**Anti-Collapse Constraints**

This is key to preventing character deformation and frame flashing. Especially for frames with people, it's recommended to add:

Clear face without distortion, proper facial features, normal body structure, natural proportions, natural movements, no extra people, no watermarks or text, stable frame without flashing.

**Complete Example**

15 seconds, 9:16 vertical, 4K ultra-high definition, cinematic texture, smooth footage without stuttering or flashing. A 20-year-old East Asian young woman with long straight black hair, gentle smile, wearing a white cotton linen dress, slowly walking on the beach at sunset, gentle breeze ruffling her hair and dress hem, turning to look at the camera, golden sunset warm light casting on her, warm orange tones. Medium eye-level shot, camera tracking smoothly, background blur, healing and fresh style. Clear face without distortion, proper facial features, normal body structure, natural flowing movements, no extra people.

## Common Prompt References

Here are some commonly used prompts you can use directly when needed.

**Camera Movement**

Basic: slow push in, quick zoom in, smooth pan, left/right pan, up/down tilt, fixed camera, smooth tracking, follow shot, slow pull out, zoom magnification, circular movement, boom shot, dolly through shot

Advanced: Steadicam-level smooth pan, breathing push in + slight zoom, Hitchcock-style vertigo zoom, Inception-style axis roll, tornado-style spiral orbit, bullet time slow motion, hydraulic arm vertical floating feel, drone probe perspective spiral descent, focus rack transition, one-take

**Camera Angles and Framing**

Framing: close-up, medium close-up, medium shot, wide shot, extreme wide shot, extreme close-up, bird's eye view, god's eye view

Angles: eye level, over-the-shoulder shot, low angle looking up, high angle looking down, macro perspective, fisheye lens, voyeuristic composition, POV first-person perspective, frame-within-frame composition

**Lighting and Color Tone**

Lighting: natural light, soft light, hard light, side light, backlight, top light, bottom light, warm light, cool light, golden hour sunset light, candlelight, neon light, god rays, rim light, volumetric light

Color tone: warm tones, cool tones, high saturation, low saturation, vintage tones, film grain, black and white grayscale, macaron palette, Morandi palette, blue-purple contrast colors

**Common Styles**

Healing and fresh: natural light, soft tones, clean and healing, warm and comfortable

Japanese literary: low saturation, clean and transparent, Japanese atmosphere, gentle and aesthetic

Vintage film: slight grain, vintage tones, film texture, nostalgic atmosphere

Cyberpunk: neon lights, blue-purple contrast, tech futuristic feel, dark tones advanced

Ancient Chinese style: ink painting mood, ancient architecture, flowing hanfu, classical elegance

Advanced dark tones: low brightness, high contrast, minimalist clean, luxury texture

Hong Kong retro: 1980s atmosphere, vintage filter, Hong Kong-style street photography, film grain

Documentary feel: raw natural light, lifestyle, authentic simplicity, documentary sense

Sci-fi future: future cities, floating architecture, tech lighting, cyber texture

Martial arts realm: bamboo forest swordsman, leaping across rooftops, flowing garments, martial arts mood

**Anti-Collapse Negative Prompts**

--no blurry, low quality, deformed, extra fingers, hand collapse, facial distortion, incorrect body structure, frame tearing, mosaic, cluttered background, plastic feel, excessive frame shaking, watermarks, extra text, overexposed, dark face, frame flashing, ghosting

## How to Maintain Character and Frame Consistency

When making long videos, the most frustrating issue is: the character generated in the first segment changes face, clothes, and hairstyle in the second segment. When pieced together, they're clearly not the same person, and the visual style jumps around too.

Here are some methods I commonly use:

**Reference Photo Method**

This is the most effective method for dealing with character face-changing.

First use text-to-image to generate a photo of the character you're most satisfied with, with facial features, hairstyle, and clothing all determined—this is your "reference photo." Every time you generate a video, upload this reference photo and write in the prompt: @Image1 as character reference photo, strictly preserve the character's appearance, hairstyle, clothing, and facial features from the reference image, maintain consistency throughout. Using the same reference photo for all segments will basically prevent the character from changing face or outfit.

**@Material Reference Method**

This is a core feature of Seedance 2.0. Each image and video you upload will generate a corresponding material name. Using **@+material name** in your prompt clearly tells the AI what this material is for.

Some reference examples:

Character consistency: @Image1 as protagonist, maintain character's appearance, hairstyle, and clothing completely consistent throughout

Camera movement consistency: Completely reference the camera effects and movements from @Video1

Action consistency: @Image1's character, completely replicate the dance movements from @Video1

Style consistency: Overall frame style, color tone, and lighting completely reference @Image2, maintain consistency throughout

**Fixed Parameters and Unified Style Keywords**

This is the most basic operation:

All segments use the same resolution (1080P/2K), same aspect ratio (9:16/16:9), same duration.

Every segment's prompt uses the exact same style keywords, quality keywords, and color tone keywords. For example, if the first segment writes "healing and fresh, warm orange tones, 4K ultra-high definition, cinematic texture," all subsequent segments must include this verbatim—don't change the wording, or the visual style will definitely jump.

**First-Last Frame Lock Method**

To seamlessly connect two video segments, use this method:

After generating the first video segment, open it in a player, drag to the last 0.5 seconds, capture a clear image, and save it as "Segment 1 ending frame." When generating the second video segment, upload this ending frame image and write in the prompt: @Image1 as video opening frame, maintain frame content, characters, and style completely consistent with the opening frame, actions naturally continue. Follow this pattern, using each segment's ending frame as the next segment's opening, and the pieced-together segments will be quite smooth.

## How to Create Long Videos

Seedance 2.0 can generate a maximum of 15 seconds per generation. To create 1-3 minute long videos, you need to piece together multiple segments.

Here's my workflow:

**Step One: Write a Shot List**

Don't start writing prompts right away—write a shot list first. A shot list isn't wasting time; it saves you time.

The shot list needs to include:

Total duration: 1 minute/2 minutes/3 minutes

Number of segments: 1 minute suggests 4-6 segments, 2 minutes 8-12 segments, 3 minutes 12-18 segments

Core content of each segment: One shot only covers one action, one scene

Transition method: How this segment connects to the next

Style requirements: Unified style, quality, and color tone throughout

**1-Minute Shot List Example**

Segment 01 (0-10s): Protagonist sits at wooden desk, hands on desk, looks up at camera and smiles. Warm and healing, soft light, 4K HD, stable face without distortion.

Segment 02 (10-20s): Protagonist's right hand picks up white ceramic cup, lightly touches lips to drink hot beverage, natural gentle movement. Same as above, continuous movement, same character outfit unchanged.

Segment 03 (20-30s): Sunset slowly sets outside window, golden light casting on desk, empty frame. Same as above, warm light atmosphere, smooth footage.

Segment 04 (30-40s): Protagonist looks at camera again, speaks softly, natural lip sync. Same as above, medium shot push in, character features completely consistent.

Segment 05 (40-50s): Subtitles appear: Today is also gentle, background blur. Same as above, unified color tone, stable frame.

Segment 06 (50-60s): Protagonist smiles looking out window, frame gradually warms to close. Same as above, healing style, wide shot pull out.

**Step Two: Write Prompts for Each Segment Following the Shot List**

After writing the shot list, write prompts for each segment. A few points to note:

Every segment must repeat the exact same style keywords, quality keywords, and color tone keywords—don't change them.

For segments with characters, the first sentence must write "Same protagonist, appearance, clothing, and hairstyle completely consistent with segment 01's character," while uploading the reference photo.

Write actions slowly and continuously—"slowly turning" has a 30% higher success rate than "quickly spinning."

Write only one camera movement at a time—"slow push in" works, but "push in then orbit then pull out" is prone to failure.

**Step Three: Generate Segments in Sequence**

After writing prompts, generate in sequence: segment 01→segment 02→segment 03—don't randomize the order.

Two tips here:

To make two segments connect more naturally, use the "first-last frame lock method" mentioned earlier, using the previous segment's ending frame as the next segment's opening frame.

After generating and downloading each segment, immediately rename it to "Segment 01," "Segment 02"—don't skip this, or you won't be able to tell which is which during editing.

**Step Four: Edit and Piece Together**

After all segments are generated, you can use editing software like CapCut to piece together the complete video. Both mobile and desktop versions work.

Basic assembly:

Create a new project, select the same aspect ratio as used during generation (16:9 horizontal/9:16 vertical).

Drag segments 01-06 onto the timeline in sequence, start with hard cuts, just make sure it plays through completely.

Mute or lower the original audio from individual segments, use a single unified BGM for the entire piece to avoid audio jumps.

Advanced optimization:

Transitions: Mainly use hard cuts, add fade in/fade out or dissolve transitions when necessary.

Subtitles: Use the automatic subtitle recognition feature, select a font matching the style.

Color grading: Use the same filter/color grading parameters to unify the color tone throughout.

Sound effects: Add matching sound effects to key actions, like footsteps, wind, cup clinking.

After everything is done, export at 1080P 30fps.

## Common Issues and Solutions

Here are some issues I encountered during use and their solutions:

**Prompt Information Overload**

Writing seven or eight subjects and more than ten actions in one prompt means the AI doesn't know what the focus is, resulting in messy footage. Recommendation: One prompt should have no more than 2 core subjects, no more than 3 core actions, and no more than 10 modifiers.

**Overly Complex Actions Causing Frame Collapse**

Don't write fighting, running, jumping, vigorous dancing, or complex multi-person interactions—the AI is prone to generating deformed limbs and collapsed frames. Prioritize slow, continuous, gentle actions.

**Uploading Reference Materials Without Marking in Prompts**

Uploading images and videos but not telling the AI what the materials are for in the prompt is essentially useless. You must use @material name to explicitly tell the AI what to reference from each material.

**Different Style Keywords and Parameters for Each Segment**

Segment 01 writes "healing atmosphere," segment 02 writes "cyberpunk," segment 03 writes "ancient Chinese style"—the final pieced video will definitely have severe style jumps. For all segments throughout, use the same set of style keywords, quality keywords, resolution, and aspect ratio.

**Not Writing a Shot List and Just Generating**

Without a shot list, blindly generating will only result in a bunch of fragmented segments that can't be pieced into a complete story.

**Incorrect Duration Settings for Video Extension**

When using the video extension feature, the selected duration is for the newly added segment, not the total duration of the entire video.

**Choosing the Wrong Entry Point**

Seedance 2.0 has two core entry points: "First-Last Frame" entry is suitable for simple situations with one image + one text; "All-Reference" entry is for situations with multiple images, videos, and audio materials. If unsure, just choose "All-Reference."

**Frame Flashing and Shaking**

Add to the prompt: "stable frame, no flashing, no ghosting, smooth motion, fixed camera position" to solve most flashing issues.

**Character Deformation and Collapse**

Besides using reference photos to fix characters, add negative prompts at the end to prohibit the AI from generating deformed or collapsed frames.

**Blindly Pursuing High Resolution**

When testing, don't go straight to 4K or 2K—first use 480P/720P to quickly test ideas and prompts. Once satisfied with the result, then use 1080P to generate the final version.

## Some Usage Insights

Seedance 2.0 is just a creative tool. It can help you realize video ideas with zero barriers, saving time and effort. You don't need to know how to shoot or edit to create video works.

But it can't replace creativity and ideas. No matter how well-written the prompts or how skilled you are with camera techniques, what ultimately makes your work moving is still the story, emotion, and creativity inside.

If you're just starting out, don't immediately try to create complex long videos or flashy special effects. Start practicing with 15-second short clips, get familiar with basic prompts, character consistency, and camera techniques, and you'll gradually be able to create the works you want. Don't be afraid of failures—every generation is accumulating experience.

Tools are just means; creativity is the core of the work.

## Official Resources and Access

For easy access to Seedance 2.0, here are the official URLs:

**ByteDance Seed Official Release Page**: [https://seed.bytedance.com/zh/blog/official-launch-of-seedance-2-0](https://seed.bytedance.com/zh/blog/official-launch-of-seedance-2-0)

**Jimeng AI (Core Experience Platform)**: [https://jimeng.jianying.com](https://jimeng.jianying.com)

**VideoDance (Seedance 2.0 Convenient Entry)**: [https://videodance.cc](https://videodance.cc)

As a reliable Seedance 2.0 China website, VideoDance provides quick and convenient access to this powerful video generation tool.
