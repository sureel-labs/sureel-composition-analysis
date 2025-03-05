# Composition vs. Recording in AI Music

This repository accompanies our research paper "Evaluating the Role of Composition and Recording Style in AI Music", currently under review at IEEE ResGenXAI 2025.
Here, we summarize the data used for our experimental validation in more detail.

A link to the paper will be added upon publication.

## Song Selection

We use two datasets of songs in our paper: a composition dataset, and a recording dataset.
Each datasets consists of five sets of songs that share a common property.
Both are shown in detail next.

### Composition Sets

We use five sets with identical musical composition.
For that, we chose five popular songs from five different genres that each had been covered a sufficient amount of times.
Then, we collect nine cover songs for each original track to obtain a total of ten versions of each composition.
The following original tracks and covers were selected to ensure a range of different genres from different decades:

**Rock**: 
* Original track: ["Tutti Frutti"](https://www.youtube.com/watch?v=F13JNjpNW6c), released by Little Richard in 1955
* Cover versions: [Elvis Presley](https://www.youtube.com/watch?v=zCulj2AbOGc), [L'Amour Girls Band](https://www.youtube.com/watch?v=bgcYFQvQ70A), [School of Rock AllStars](https://www.youtube.com/watch?v=bd6xs2p0x0g), [Acapella en Español](https://www.youtube.com/watch?v=m7tSGJZqQ1k), [Don Blues Band](https://www.youtube.com/watch?v=k6r7qJ5gUFk), [Nico Brina](https://www.youtube.com/watch?v=3KVvyox0NOE), [DJ Bx'treme](https://www.youtube.com/watch?v=D73ZFuzEzJI), [Blues Cover](https://www.youtube.com/watch?v=SpBzwbdW9kQ), [Instrumental Cover](https://www.youtube.com/watch?v=5lCwx2D8uhk)

**Pop**: 
* Original track: ["Sound of Silence"](https://www.youtube.com/watch?v=l0q7MLPo-u8), released by Simon & Garfunkel in 1964
* Cover versions: [Pentatonix](https://www.youtube.com/watch?v=gdVjVtpr55M), [Gregorian](https://www.youtube.com/watch?v=4O_BtRIkIQ4), [International String Trio](https://www.youtube.com/watch?v=5L5O_Qj0sgc), [Jazz Version](https://www.youtube.com/watch?v=rXi9WXu31sY), [Wuauquikuna](https://www.youtube.com/watch?v=ndUCNnhH03Q), [BOBAFLEX](https://www.youtube.com/watch?v=y-1D5N7Bzrk), [Tropavibes](https://www.youtube.com/watch?v=d16uCCOnukc), [Cinematic Dark Version](https://www.youtube.com/watch?v=u_CqjEeioZk), [Dan Vasc](https://www.youtube.com/watch?v=ngL8GXN6AvE) 

**Blues**: 

* Original track: ["Feelin’ Good"](https://www.youtube.com/watch?v=oHRNrgDIJfo), released by Nina Simone in 1965
* Cover versions: [Michael Bublé](https://www.youtube.com/watch?v=Edwsf-8F3sI), [Dolce Ensembles](https://www.youtube.com/watch?v=nfkE_xs4HgA), [Muse](https://www.youtube.com/watch?v=CmwRQqJsegw), [Bricusse](https://www.youtube.com/watch?v=Ej3rrzJtEGI), [EPIC VERSION](https://www.youtube.com/watch?v=lK0nyFEslKk), [Process](https://www.youtube.com/watch?v=K5FHDeqvNsQ), [Sax Cover](https://www.youtube.com/watch?v=5cVP2KZ9fwA), [Krakowski](https://www.youtube.com/watch?v=cPoQ1X_IyLM), [Thunder And Lightning](https://www.youtube.com/watch?v=c2rgQ4ousnA)
  
**Soul**:
* Original track: ["Hallelujah"](https://www.youtube.com/watch?v=ttEMYvpoR-k), released by Leonard Cohen in 1984
* Cover versions: [Lindsey Stirling](https://www.youtube.com/watch?v=5VzprYCxPBQ), [Pentatonix](https://www.youtube.com/watch?v=LRP8d7hhpoQ), [Andrea Bocelli](https://www.youtube.com/watch?v=iIiqxyIuMJk), [2500 Montréalers](https://www.youtube.com/watch?v=niuxr0QqMSg), [Graziatto](https://www.youtube.com/watch?v=j13DdAphTt8), [D-Stroyer](https://www.youtube.com/watch?v=aJ-xbi0d7dg), [NO RESOLVE](https://www.youtube.com/watch?v=CMFJpukpwK4), [Alejandro Coroxon](https://www.youtube.com/watch?v=MI0cTsAqD1Q), [Khalia](https://www.youtube.com/watch?v=ikmK9lL3HH4)
  
**Rap**: 
  
* Original track: ["Lose Yourself"](https://www.youtube.com/watch?v=xFYQQPAOz7Y), released by Eminem in 2002
* Cover versions: [Citycreed](https://www.youtube.com/watch?v=blHCo2coAMs), [Our Last Night](https://www.youtube.com/watch?v=0GX1hcivV9o), [Luca Stricagnoli](https://www.youtube.com/watch?v=9h5nEQpErJg), [Robyn Adele Anderson](https://www.youtube.com/watch?v=NeB9TSu08KU), [Endless Sundown](https://www.youtube.com/watch?v=JZLtys_iRyI), [Epic Cinematic Version](https://www.youtube.com/watch?v=8QYjhUnhf8w), [Reggae](https://www.youtube.com/watch?v=9xfMupV-ZCE), [Caio Ferraz & Anna Murakawa](https://www.youtube.com/watch?v=T7gYwl9sTQY), [Howetown Strangers](https://www.youtube.com/watch?v=qkJLfFtMIA0)
  
### Recording Sets

We use five sets with consistent recording styles. 
For that, we chose studio albums with a consistent production as recording sets.
To keep the size of each set identical, we only analyze the first ten songs of each album.
Interludes and tracks that only feature spoken words are omitted.
The following song collections were selected to ensure a range of different genres from different decades:

**Jazz**: ["Ella and Louis"](https://youtube.com/playlist?list=OLAK5uy_krHVPjgGUjZzGAWMWP_lRRJN45I_Ywb7w&feature=shared), released by Ella Fitzgerald and Louis Armstrong in 1956

**Folk**: ["The Freewheelin' Bob Dylan"](https://youtube.com/playlist?list=PLfGibfZATlGpj4XK7uSPrgpRiTXcI_VP1&feature=shared), released by Bob Dylan in 1963

**Rock**: ["Definitely Maybe"](https://youtube.com/playlist?list=OLAK5uy_lwRxjnG6q9zPRti_3Av0_iN22rYyFa9Vk&feature=shared), released by Oasis in 1994

**Rap**: ["The Slim Shady LP"](https://youtube.com/playlist?list=OLAK5uy_kqHXZBl9FyDtb2UckFaLtvT2L0HLVnqTs&feature=shared), released by Eminem in 1999

**Classical**: ["Studio Sessions"](https://youtube.com/playlist?list=PLtE8SnGWJ0jA6lAu3xoywWm8xiE3fCg6G&feature=shared), released by Simply Three in 2020

### Visualization

Below, we visualize the CLAP embeddings of the composition dataset and the recording dataset via TSNE projection.
Note that CLAP is not capable of detecting identical compositions - the compositions sets are scattered throughout the embedding space.
In contrast, recording sets are strongly clustered, indicating that CLAP correctly detected the consistent recording style.
For more experiments and elaborations on this result, refer to our paper (link will be made available after review is completed).

## Prompt Selection

For our audio-to-audio experiments, we use prompt sets that preserve either compositional or recording information.
We used ChatGPT to create two prompt sets: a composition prompt set, and a recording prompt set.
Each prompt set consists of ten prompts that describe only one of the two musical properties.
We list the exact prompts in the following.

### Composition Prompts

These ten prompts are designed to alter the composition as little as possible, while changing the recording style.
Thus, each prompt describes elements associated only with the recording style of a track.

* "A song with a lo-fi aesthetic, featuring warm analog distortion and soft crackling background noise." 
* "A track with high-fidelity studio recording quality, emphasizing clean and balanced sound across all frequencies."
* "A live concert recording with noticeable audience noise and open, reverberant acoustics."
* "A song produced with a vintage 1960s sound, using tape saturation and mono mixing."
* "An acoustic recording with minimal production, highlighting natural room reverb and close mic placement."
* "A heavily compressed track with an emphasis on loudness, characteristic of modern pop production."
* "A low-frequency heavy track with a booming bass and dark, muted midrange, typical of deep house or dub music."
* "A warm jazz recording with close-miked instruments and a soft, intimate ambiance."
* "A raw garage band recording with minimal mixing and audible imperfections in the playing and production."
* "A track recorded with high spatial imaging and surround sound effects, simulating a cinematic experience."

### Recording Prompts

These ten prompts are designed to alter the recording style as little as possible, while changing the composition.
Thus, each prompt describes elements associated only with the composition of a track.

* "A melancholic piano melody in a minor key, played at a slow tempo with repetitive arpeggios."
* "A cheerful folk tune in 6/8 time signature, featuring a bright and uplifting melody."
* "A minimalist composition based on repetitive patterns and gradual harmonic shifts."
* "A blues progression in 12-bar form with a swing rhythm and walking bassline."
* "A baroque-inspired fugue written in counterpoint, featuring a strict harmonic framework."
* "A dance track with a four-on-the-floor beat and a syncopated melodic hook in 4/4 time signature."
* "A ballad in 3/4 time, characterized by a soaring melody and rich chord progressions in a major key."
* "A cinematic orchestral composition featuring a powerful brass melody and supporting string harmonies."
* "A jazzy bebop tune with complex chord changes and an improvisatory melody line."
* "A fast-paced polyrhythmic piece with interlocking percussion and a melody that shifts between scales."


## Citation

Upon publication, an entry for citing this work will be added.

:copyright: Sureel Inc. 2025
