# addressbook
x64dbg plugin
This is **pre-release** version!
## Usage
### addtoaddrbook `no`, `addr`
Add `addr` to addressbook numbered `no`.
### delfromaddrbook `no`, `addr`
Delete `addr` from addressbook numbered `no`.
### clearaddrbook `no`
Removes addressbook `no`.
### listaddrbook `no`
List all content in addressbook `no`. If `no` is not present: List all addressbooks.
### inaddrbook(`no`,`addr`)
1 if `addr` is in addressbook numbered `no`; 0 if addressbook numbered `no` does not contain `addr`.
## Planned features
Callstackbook
