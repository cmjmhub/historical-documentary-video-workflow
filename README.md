# Jmjmcreatzvidz — Spokesperson Video Enhancer

A reusable GitHub playbook for turning **existing Talking Photos speaking videos**
into polished **new VideoExpress productions** without changing the spokesperson's
original face, voice or lip-sync.

**Source inspiration:** [ai-playbooks Historical Documentary Video Workflow](https://github.com/ai-playbooks/historical-documentary-video-workflow).
This fork has been adapted for general-purpose spokesperson enhancement rather
than recreating the historical documentary generator.

## Simple workflow

1. **Talking Photos:** Supply an existing MP4 with complete speaking performance.
2. **VideoExpress:** Import once with embedded original audio, then save a NEW
   project without overwriting the master.
3. **VideoExpress:** Make new scenes, B-roll, animations, or cutaways around that
   recorded narration. Keep original speech playing and synchronized.
4. **Finish:** Preview, export and review the edited MP4.

This does **not** require cutting out the speaker or changing their background
within the original video. Supporting images, screen recordings, and cinematic
cutaways can be composited as separate scenes. For a true person-on-new-background
cutout, a verified compatible subject-isolation/alpha workflow is required;
the tested VideoExpress green-screen filter was insufficient for the original
Talking Photos footage.

## Instructions for ChatGPT Work

Read [SYSTEM_PROMPT.md](SYSTEM_PROMPT.md) and use an authorized browser session
to inspect VideoExpress. A sample request:

> Use this playbook with my existing Talking Photos MP4. Preserve the
> character, original voice and lip-sync. Create a separate VideoExpress
> project, add two supporting visual cutaways while keeping the master
> narration intact, then export. Do not overwrite Test #3.

No external captioning, purchases, public sharing, or new voice generation
without separate authorization. If preview/listening is unavailable, disclose
what cannot be verified.

**Brand credit:** Created by Jmjmcreatzvidz.

GitHub stores the playbook text—not the actual videos, credentials, or an
editable VideoExpress project.

## Complete video from Juan's thoughts (new main mode)

Juan Martinez approved a new permanent Jmjmcreatzvidz studio spokesperson based on his photo: waist-up, black cap/sunglasses/T-shirt, dark blue-and-amber cinematic studio, confident motivational delivery. His approved source performance is `jmjm creatz my story opening.mp4`. Preserve the actual user-supplied image/voice master; neither asset is stored in this GitHub repository.

**For a new video:** Juan shares an idea -> ChatGPT drafts a spoken script and visual plan -> Juan approves -> use his existing studio reference to create a NEW Talking Photos speaking performance with a verified/reviewed matching low-baritone Mexican American male voice -> import to a NEW VideoExpress project -> assemble a complete cinematic visual story around its uninterrupted original narration -> review/export MP4. A description alone does not lock a voice, so ask for a test sample if Talking Photos lacks reusable voice-reference functionality.

**For an existing video:** continue to preserve its original performance without regenerating speech. Do not overwrite Tests #3 or #4. The step-by-step production rules are in [SYSTEM_PROMPT.md](SYSTEM_PROMPT.md).
