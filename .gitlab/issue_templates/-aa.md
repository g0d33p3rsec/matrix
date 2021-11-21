I believe this domain is an Malware domain(s) --> which should be blocked as..

- [X] Wildcarded
- [ ] Single domain blocking

```python
domain   CNAME . ; Malicious
*.domain   CNAME . ; Malicious
```

## Relevant comments
Thanks to @iam-py-test


## Screenshots


## Relevant External sources
- `https://github.com/blocklistproject/Lists/issues/562`

### All Submissions:
- [X] Have you followed the guidelines in our [Contributing](CONTRIBUTING.md)
	  document?
- [x] Have you checked to ensure there aren't other open
      [Merge Requests (MR)](../merge_requests) or [Issues](../issues) for the
      same update/change?
- [X] Have you added an explanation of what your submission do and why you'd
	  like us to include them??
- [ ] Added [screenshot](https://mypdns.org/MypDNS/support/-/wikis/Screenshot)
	  for prove of [False Negative](https://mypdns.org/MypDNS/support/-/wikis/False-Negative)

### Testing face
- [X] Checked the internet for verification?
- [X] Have you successfully ran tests with your changes locally?

### Todo
- [X] RPZ Server (Team @Spirillen)
- [X] Added to Source file

/label ~Malicious

/assign @Spirillen

/weight 5

/publish
