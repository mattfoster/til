# TIL: Today I Learned/Tools I'd Liketosharpen

This repo contains tools to help record information on stuff I learned and
tools to sharpen.

## Examples

    export TIL_DIR=~/til # Default is ~/Dropbox/til

    til That @mattfoster wrote an interesting tool to store TIL info
    # $EDITOR will appear, and you'll edit your note to you ❤'s content. 
    # Output will appear in `~/til/til/<current_timestamp>.md`

    ts Tweak my bashrc to let me type fewer chars when running ls -latrSh
    # Again, $EDITOR time, then output will appear in `~/til/ts/<current_timestamp>.md`

## Motivation

I need to think about implementing a system which lets me quickly and easily
record stuff I've learnt and stuff I want to improve on.

Thoughtbot has a [repo](https://github.com/thoughtbot/til
) called TIL, in which various bits of useful info are stored as markdown files.

And then there's [this](https://github.com/thoughtbot/til/blob/master/vim/custom-command.md
) custom vim command which opens a markdown file.

But, I want something easy to use on different boxes,  without having to worry
about clobbering notes, so perhaps I want different files. Maybe my custom
command should open a new MD file in a git repo which auto-pushes to my VPS?

I think something which automatically makes a list of new stuff would be fun
too, maybe with tags.

Would this also work with 'tool sharpening' ideas? I saw a peepcode screencast
where someone had a file in dropbox in which they listed stuff that they wanted
to make faster. I want to emulate this.

## Frontmatter?

I decided to add YAML front matter in case I end up managing to integrate this
with something! It also seemed a nice way to add tags.
