I report this [Drugs][catinfo] related domain to be added into the [MyPDNS RPZ Firewall][mpdrf]

```
(input your domain name here)
```

- [X] Wildcarded
- [ ] Individual domain blocking

## RPZ (Response Policy Zone) Rules

```css
domain_name_here   CNAME . ; Drugs
*.domain_name_here   CNAME . ; Drugs
```

### Additional requirements for

#### [hosts] and [Pi-hole]

```css
null
```

```css
+ www
- www
www.
```

#### Adblocker
<details><summary>Click to expand</summary>

```css
N/A
```

</details>

## Screenshots
(Upload your screenshot here)

## Comments
<!-- Comments such as specific URL to view contents -->

## My Privacy DNS issues
- `` #matrix-

## External sources
<!-- if you took this domain from other board -->
- ``

### All Submissions:
- [ ] Have you followed the guidelines in our [Contributing](CONTRIBUTING.md) document?
- [ ] Have you checked to ensure there aren't other open [Merge Requests (MR)][MR] or [issue] for the same update/change?
- [ ] Have you added an explanation of what your submission do and why you'd like us to include them??
- [ ] Added [screenshot] for prove of [False Negative][FN]

### Testing face
- [ ] Checked the internet for verification?
- [ ] Have you successfully ran tests with your changes locally?

### Todo
- [X] RPZ Server
- [X] Added to Source file

#### Logger output

<details><summary>3rd party Domains</summary>

```css
N/A
```

</details>

[catinfo]: https://0xacab.org/my-privacy-dns/support/-/wikis/Categories/Drugs
[FN]: https://0xacab.org/my-privacy-dns/support/-/wikis/False-Negative "About False Positive"
[hosts]: https://0xacab.org/my-privacy-dns/support/-/wikis/dns/DnsHosts "Hosts files a outdated blacklist format"
[issue]: https://0xacab.org/my-privacy-dns/matrix/-/issues "My Privacy DNS Domain records"
[mpdrf]: https://0xacab.org/my-privacy-dns/matrix/ "My Privacy DNS RPZ Firewall Filter"
[MR]: https://0xacab.org/my-privacy-dns/matrix/-/merge_requests "My Privacy DNS Merge Requests"
[Pi-hole]: https://0xacab.org/my-privacy-dns/matrix/-/blob/master/source/porn_filters/README.md#pi-hole "What is Pi-hole and it limitations"
[screenshot]: https://0xacab.org/my-privacy-dns/support/-/wikis/Screenshot "What is a screenshot"

/label ~Drugs

/weight 2

/publish

/severity low

/health_status on_track
