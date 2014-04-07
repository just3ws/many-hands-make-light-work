Many Hands Make Light Work
==========================

Help make UGtastic awesome by contributing show-notes, episode descriptions, transcripts, etc.

UGtastic is a celebration of the the awesome work that so many people are putting
in to build  a vibrant and exciting global technical community. But it's more than
I can handle, there's a lot of content that needs to be created beyond the video.
I have fallen way, way behind in creating show notes, summaries, transcripts, and
close-captioning files. So I'm asking your help to create them.

## How to contribute.

*   Write up or edit a summary.

    The simplest way to get started is by writing up a summary of an interview. It
    doesn't have to be long nor does the language have to be perfect. If you can do
    even a quick summary of the interview that will be very helpful. Or, maybe there
    already is a summary of an interview written. Feel free to expand or improve the
    grammar.

*   Create or expand the show-notes

    Interviews often mention projects, companies, other people. Calling out the highlights
    from the interview and adding links to more information will greatly improve the
    usefulness of the videos for other visitors.

*   Transcribe interviews

    Are you a fast typer? Or at least are you patient? Transcribing videos is hard work
    and very valuable to visitors who aren't able to hear or chose not to listen to the
    interviews but would like to know what was said. This goes a long way towards
    translating and eventually Closed Captioning as well.

*   Closed Captioning

    This is the Holy Grail of contributions. If you are willing to write up SubRip
    formatted Closed Caption files for interview episodes then you will be my new
    personal hero. These are especially valuable because they can be loaded straight
    into the videos so hard of hearing people can also enjoy the videos as well as
    being able to extract transcripts. This is a double-whammy.


*   Translations

    Translations would probably make me cry. Knowing that UGtastic could be share with
    people from different cultures and languages would be amazing.


## Where to start.

### Structure

The `interviewsi/general/example` directory holds a sketch of the structure for the files.

- `summary.markdown`: The default of the episode in Markdown format for English.
- `show-notes.markdown`: The default show notes in Markdown format for English.
- `transcript.txt`: The default transcript in plain text form for English.
- `caption.srt`: The default Closed Caption file in [SubRip](http://en.wikipedia.org/wiki/SubRip) format for English.
- `pl`: An example directory that could hold Polish translations of the default files.

The interviews are organized as `conferences/$CONFERENCE_NAME/$YEAR/$INTERVIEW\_NAME`
or `general/$INTERVIEW\_NAME` interview.

        interviews
        ├── conferences
        │   ├── chicagowebconf
        │   │   └── 2012
        │   ├── goto\ chicago
        │   │   └── 2013
        │   ├── software\ craftsmanship\ north\ america
        │   │   ├── 2011
        │   │   ├── 2012
        │   │   └── 2013
        │   ├── webvisions\ chicago
        │   │   └── 2013
        │   └── windycityrails
        │       └── 2012
        └── general
            └── example
                ├── caption.srt
                ├── pl
                │   └── README.markdown
                ├── show-notes.markdown
                ├── summary.markdown
                └── transcript.txt


So if you wanted to translated the interview with Rich Hickey from GOTO Chicago 2013
then you would create a folder `interview/conferences/goto chicago/2013/rich hickey`
and start adding the text files inside there.

### Git commits and pull requests

Please put the name of the interview in the commit request. I'll be able to figure it
out quickly from reading the pull request but it'll make the history a lot easier
to parse.

## License and attribution

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International license. You must agree to sharing under this license before contributing. Thanks.
