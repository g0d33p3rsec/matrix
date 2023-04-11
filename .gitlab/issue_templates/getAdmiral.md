I report this ~Tracking [related][catinfo] domain to be added into the [MyPDNS RPZ Firewall][mpdrf]

## Reported URL

```css
(input your URL here)
```

- [X] Wildcarded
- [ ] Individual domain blocking

## RPZ (Response Policy Zone) Rules

```css
domain_name_here   CNAME . ; Tracking
*.domain_name_here   CNAME . ; Tracking
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
![image](https://0xacab.org/my-privacy-dns/support/uploads/9baedebe69aa576d9d0ddd1309eb0128/admiral.jpg)

## Comments
This domain is used by `getadmiral.com` to collect your surfing habits and the are using a variety of scripts to generate a personal identification of you and your devices.
You can always find the latest list of Admiral's Active domains in milestone %"getadmiral.com"


## External sources
<!-- add source URL here if you take it from somewhere else -->


## My Privacy DNS issues
| Domain | FQDN | Issue |
| -- | -- | -- |
| - | - | - |

### Todo
- [X] Added to Source file
- [X] Added to RPZ zone


[catinfo]: https://0xacab.org/my-privacy-dns/matrix/-/tree/master/source/tracking
[mpdrf]: https://0xacab.org/my-privacy-dns/matrix/
[hosts]: https://0xacab.org/my-privacy-dns/support/-/wikis/dns/DnsHosts
[Pi-hole]: https://0xacab.org/my-privacy-dns/matrix/-/blob/master/source/porn_filters/README.md#pi-hole

[//]: # ( write SHA-1 value of base domain here )

/milestone %"getadmiral.com"

/label ~Tracking

/severity critical
