# RssSpider

This is an extension to [audio_book_creator].
Instead of being a cli, it is a webapp. It is focused
on serving rss instead of audiobooks.

This has 2 purposes

- Testing viability of using the phone
itself to generate voice from text (vs generation a m4b file)
- Use recent web technologies

Goals:

- [ ] spiders site to fetch pages for articles / books
- [ ] rss feed to serve books to phone
- [ ] background job queue to spider
- [ ] Uses ajax/pjax? forms to view and add status
- [ ] Uses websockets to display status
- [ ] cli to submit jobs
- [ ] metrics to gather statistics on use / usability

[audio_book_creator]: https://github.com/kbrock/audio_book_creator
