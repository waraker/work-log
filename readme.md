# Work Log Sublime Text Package WIP

A simple work log syntax highlighter for Sublime Text

## Syntax

	`# 1.1.13`				Log date.
	`12:00 description`		Log start time with description.
	`13:00 b`				Log end time. Sets a break and ends the the current duration.
	`14:00 #TagName:`		Tag for client/project, same as above but enables grouping of durations.


## Example Work Log file:

`work.wl`

	# 6.9.13
	10:00 standard task
	11:00 b
	12:30 #ProjectName: tagged entry task
	13:30 b

	# 7.9.13
	11:30 update readme, push commits
	11:40 b