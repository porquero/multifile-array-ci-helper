multifile-array-ci-helper
=========================

Helper to make possible use Codeigniter with array names for form files.

If you need to use multiple files to upload in a form using array names (like files[]) with Codeigniter is not possible. Besides, $_FILES schema is not compatible with $this->upload->do_upload().
With this helper you can use this kind of names to make it possible. Only use an array name for all files in a form and use the helper:
