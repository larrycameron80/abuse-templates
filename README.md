# Abuse Templates
Templates for dealing with relay abuse notifications

## Templates

All templates are actually bash scripts which end in `.template`, which are sourced in and MUST be syntactically valid bash. Please keep output widths to 80 columns.

*	GENERIC - A response which satisfies the majority of notifications.
*	DMCA - A response which satisfies DMCA complaints.

## Script Usage

On OSX, you can pipe into pbcopy to copy to clipboard to quick pasting into an email.

```
./gen-abuse-reply.bash <template> <IP> | pbcopy
```

On Linux, the same thing should work with xclip.

```
./gen-abuse-reply.bash <template> <IP> | xclip
```

