# ansible-manage-lvm

Ansible role to manage LVM Groups/Logical Volumes.

> NOTE: Can be used to create, extend or resize LVM Groups and volumes.

## ⚠️ Important: Ansible Galaxy Role Name

**As of December 2025**, this role is available on Ansible Galaxy as:

```yaml
- src: mrlesmithjr.manage_lvm  # Note: underscore, not hyphen
```

The previous role names (`mrlesmithjr.manage-lvm` and `mrlesmithjr.manage_lvm`) were
consolidated into a single role. If you were using `mrlesmithjr.manage-lvm`, please
update your `requirements.yml` to use `mrlesmithjr.manage_lvm`.

**Note:** This role is used by [OpenStack Kayobe](https://docs.openstack.org/kayobe/latest/)
for LVM management. The `manage_lvm` name was preserved to maintain compatibility.

### Historical Download Statistics

Prior to consolidation, this role had accumulated significant usage:

| Role Name | Downloads (as of Dec 2025) |
|-----------|---------------------------|
| `mrlesmithjr.manage_lvm` | 697,492 |
| `mrlesmithjr.manage-lvm` | 494,517 |
| **Combined Total** | **1,192,009** |

Due to Ansible Galaxy limitations, download counts reset when roles are re-imported.
The historical data above represents the actual community usage of this role.

## Requirements

Devices/disks to be members of the LVM setup **must be** identified prior to
using this role.

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

None

## Example Playbook

[playbook.yml](playbook.yml)

## License

MIT

## Author Information

Larry Smith Jr.

- [@mrlesmithjr](https://twitter.com/mrlesmithjr)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)
- [http://everythingshouldbevirtual.com](http://everythingshouldbevirtual.com)

<a href="https://www.buymeacoffee.com/mrlesmithjr" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
