# ProPresenter Docs

## Adding New Songs
Before adding a new song, verify that it is not already in ProPresenter. If the song exists but needs modifications, go to [Editing Songs](#editing-and-arranging-songs). Ensure there are no duplicates of the same song; different versions need to be different arrangements.

### Option #1: Creating A New Presentation
1. Select `File > New Presentation` or use `Command+N`.
2. The filename should be the exact song title.
3. Choose the `Singing Main` theme.
4. Save to the appropriate Library (commonly `Youth Songs`) and add to the relevant Playlist (typically `Youth Service`).
5. Access the reflow editor.
6. Input all unique verses and choruses. Each chorus should be unique, even if it repeats.
7. Create a `Main` arrangement by following the guidelines in [Editing Songs](#editing-and-arranging-songs).

### Option #2: Importing From a .txt File
Ensure the song text file follows this format:
```
Title: Exact Song Title

Verse 1
Verse 1 lyrics text
More Verse 1 lyrics text

Chorus
Chorus lyrics text
More Chorus lyrics text

Verse 2
Verse 2 lyrics text
More Verse 1 lyrics text

Verse 3
Verse 3 lyrics text
More Verse 3 lyrics text
```

1. Navigate to `File > Import > File...`.
2. Select and import the .txt file.
3. Verify the `Singing Main` theme is applied.
4. Save to the suitable Library (usually `Youth Songs`) and Playlist (typically `Youth Service`).
5. Edit the imported content, removing redundant choruses and regrouping slides as needed.
6. For detailed editing and arranging instructions, see [Editing Songs](#editing-and-arranging-songs).

### Option #3: Importing From PowerPoint (pptx)
1. Acquire a PowerPoint (.pptx) file. Convert other formats (e.g., Google Slides, Keynote) to .pptx.
2. Use a terminal command to convert the .pptx file into a .txt file. It should output in a ProPresenter ready format.
    1. 'pp_to_txt' + Space + drag pptx file to terminal + Enter
    2. File will be saved to desktop. 
3. Review and tweak the text file to ensure correct title and grouping. Valid group names include: Verse, Verse (1-6), Chorus, Chorus (1-4), Bridge, Bridge (1-3), Pre-Chorus, Tag, Intro, Outro, Interlude, Vamp, Turnaround.
4. Follow the text file import process outlined in Method 2.

## Editing and Arranging Songs

### Song Structure
- The master arrangement should encompass every verse and chorus variation, including translations
- Repeating sections (chorus, bridge) should appear only once in the master version.
- Create a `Main` arrangement where all repeated sections are correctly placed.
- To split slides correctly the second split slide should have no label deliberatly assigned to it so that both slides appear as one component in the arrangments.
- Any slide exceeding 4 lines should be divided into two slides next to each other so that the group of the second split part is inhierted from the first part of the split slide.

    ```
    Original Slide:
    Chorus- "This is a part of the chorus that is 4 lines long, This is a part of that is also 4 lines long"
  
    New Slide:
    Slide 1 Chorus - "This is a part of the chorus that is 4 lines long"
    Slide 2 Chorus  "This is a part of that is also 4 lines long"   (This slide should have no group assigned)
    ```
- Create separate slides for repeated sections within a verse or chorus.

    ```
    Original Slide:
    Chorus - "This ia the text from a chorus and is sang once. But this part is sang twice"
  
    New Slide:
    Slide 1 Chorus - "This ia the text from a chorus and is sang once, But this part is sang twice"
    Slide 2 Chorus - "But this part is sang twice"   (This slide should have no group assigned)
    ```

#### Main Arrangement Details
- Follow the original song's structure when arranging verses and choruses in the `main` arrangement.
- Form specific arrangements for uncommon song variations, like `w/English` or `w/Russian`.
- Repeat any verses or choruses in the arrangement if they are repeated in the song. So if a chorus repeats there should be two choruses next to each other in the arragement.

#### Guidelines for Naming Arrangements
- `Master`: A comprehensive version with all the song's unique components.
- `Main`: The main composition that mirrors the original song structure. 
- `w/Russian`: An English song with Russian inclusions.
- `w/English`: A Russian song with English inclusions.

### Sample Song Arrangements

#### Simple Composition
- **Master**: `Verse 1 | Chorus | Verse 2 | Verse 3`
- **Main**: `Verse 1 | Chorus | Verse 2 | Chorus | Verse 3 | Chorus`

#### Composition With Chorus Reapeat
- **Master**: `Verse 1 | Chorus | Verse 2 | Verse 3`
- **Main**: `Verse 1 | Chorus | Chorus | Verse 2 | Chorus | Chorus | Verse 3 | Chorus | Chorus`

#### Composition with a Bridge
- **Master**: `Verse 1 | Chorus | Verse 2 | Verse 3 | Bridge`
- **Main**: `Verse 1 | Chorus | Verse 2 | Chorus | Verse 3 | Chorus | Bridge | Chorus`

#### English Composition w/Russian
- **Master**:`Verse 1 | Verse 1(Russian Version) | Chorus | Chorus(Russian) | Verse 2 | Verse 2(Russian)`
- **Main**:`Verse 1 | Chorus | Verse 2 | Chorus`
- **w/Russian**:`Verse 1 | Chorus | Verse 2 | Chorus | Verse 2(Russian) | Chorus(Russian)`

