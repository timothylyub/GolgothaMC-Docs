# ProPresenter Procedures

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

Procedure:
1. Navigate to `File > Import > File...`.
2. Select and import the .txt file.
3. Verify the `Singing Main` theme is applied.
4. Save to the suitable Library (usually `Youth Songs`) and Playlist (typically `Youth Service`).
5. Edit the imported content, removing redundant choruses and regrouping slides as needed.
6. For detailed editing and arranging instructions, see [Editing Songs](#editing-and-arranging-songs).

### Option #3: Importing From PowerPoint (pptx)
1. Acquire a PowerPoint (.pptx) file. Convert other formats (e.g., Google Slides, Keynote) to .pptx.
2. Use a terminal command to convert the .pptx file into a .txt file. It should output in a ProPresenter ready format.
3. Review the converted text, adjusting titles and group names for accuracy. Valid group names include: Verse, Verse (1-6), Chorus, Chorus (1-4), Bridge, Bridge (1-3), Pre-Chorus, Tag, Intro, Outro, Interlude, Vamp, Turnaround.
4. Follow the steps in Option #2 for importing from a .txt file.

## Editing and Arranging Songs

### Song Structure
- Include every verse and variation in the master arrangement, considering translations.
- Repeating sections (chorus, bridge) should appear only once in the master version.
- Create a `Main` arrangement where all repeated sections are correctly placed.
- Any slide exceeding 4 lines should be divided into two connected slides.

#### Main Arrangement Details
- Arrange verses and choruses to mirror the original song's sequence.
- The `Main` arrangement should only include verses typically sung.
- Exclude uncommon variations from the `Main` arrangement; create specific arrangements for them (e.g., `w/English`, `w/Russian`).
- Repeat any verses or choruses in the arrangement if they are repeated in the song. So if chorus repeats there should be two choruses nest to each pther in the arragement
- Create separate slides for repeated sections within a verse or chorus.

#### Arrangement Naming Scheme
- `Master`: The comprehensive version containing all unique elements of the song.
- `Main`: An arrangement closely resembling the original song, typically used.
- `w/Russian`: An English arrangement with Russian elements.
- `w/English`: A Russian arrangement with English elements.

### Example Arrangements

#### Simple Song
- **Master**: `Verse 1 | Chorus | Verse 2 | Verse 3`
- **Main**: `Verse 1 | Chorus | Verse 2 | Chorus | Verse 3 | Chorus`

#### Simple Song With Chorus Reapeat
- **Master**: `Verse 1 | Chorus | Verse 2 | Verse 3`
- **Main**: `Verse 1 | Chorus | Chorus | Verse 2 | Chorus | Chorus | Verse 3 | Chorus | Chorus`

#### Song With Bridge
- **Master**: `Verse 1 | Chorus | Verse 2 | Verse 3 | Bridge`
- **Main**: `Verse 1 | Chorus | Verse 2 | Chorus | Verse 3 | Chorus | Bridge | Chorus`

#### English Song w/Russian
- **Master**:`Verse 1 | Verse 1(Russian Version) | Chorus | Chorus(Russian) | Verse 2 | Verse 2(Russian) | Verse 3 | Verse 3(Russian)`
- **Main**:`Verse 1 | Chorus | Verse 2 | Chorus | Verse 3 | Chorus`
- **w/Russian**:`Verse 1 | Chorus | Verse 2 | Verse 3 | Chorus | Verse 3(Russian) | Chorus(Russian)`

