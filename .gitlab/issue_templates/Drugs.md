I report this [Drugs] related domain to be added into the [MyPDNS RPZ Firewall][mpdrf]

```
(please input basedomain here)
```

- [X] Wildcarded
- [ ] Individual domain blocking

## RPZ (Response Policy Zone) Rules

```css
domain   CNAME . ; Drugs
*.domain   CNAME . ; Drugs
```

### Additional requirements for

#### [hosts] and [Pi-hole]
<details><summary>Click to expand</summary>

```css
NULL
```

```css
+ www
- www
www.
```

</details>

#### uBlock Origin adblocker
<details><summary>Click to expand</summary>

```css
N/A
```

</details>

## Screenshots


## Comments
<!-- Be as clear as possible: nobody can read your mind, and nobody is looking at your issue over your shoulder. -->

## My Privacy DNS issues
- `` #

## External sources
<!-- If you found this domain on another issueboard -->
- ``

### All Submissions:
- [ ] Did you follow the guidelines in the [Contributing](CONTRIBUTING.md)
	  document?
- [ ] Have you added an explanation of what your submission do and why you'd
	  like us to include them??
- [ ] Have you checked to ensure there aren't other open
      [Merge Requests (MR)][MR] or [issue] for the same update/change?
- [ ] Added [screenshot] for prove of [False Negative][FN]

### Testing phase
- [ ] Checked the internet for verification?
- [ ] Successfully tested changes locally?

### Todo
- [X] RPZ Server (Team \@Spirillen)
- [X] Added to Source file

[Drugs]: https://mypdns.org/MypDNS/support/-/wikis/Categories/Drugs
[FN]: https://mypdns.org/MypDNS/support/-/wikis/False-Negative "About False Positive"
[hosts]: https://mypdns.org/mypdns/support/-/wikis/dns/DnsHosts "Hosts files a outdated blacklist format"
[issue]: https://mypdns.org/my-privacy-dns/matrix/-/issues "My Privacy DNS Domain records"
[mpdrf]: https://mypdns.org/my-privacy-dns/matrix/ "My Privacy DNS RPZ Firewall Filter"
[MR]: https://mypdns.org/my-privacy-dns/matrix/-/merge_requests "My Privacy DNS Merge Requests"
[Pi-hole]: https://mypdns.org/my-privacy-dns/matrix/-/blob/master/source/porn_filters/README.md#pi-hole "What is Pi-hole and it limitations"
[screenshot]: https://mypdns.org/MypDNS/support/-/wikis/Screenshot "What is a screenshot"

/label ~Drugs

/weight 2

/publish

/severity low
