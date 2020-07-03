# Planning out work

## Init
- [ ] create base components eg. top navbar, body, bottom navbar

## Create storage
- [ ] replace `Dexie` with probably just plain state or maybe context not sure
    - using SQLite since it has related tables
        - referencing [this](https://dev-yakuza.github.io/en/react-native/react-native-sqlite-storage/)

## Figure out how to use camera/store/show images
- new to me eg. not using html images

## Build out all the pages
- [ ] addresses
    - [ ] single address
        - [ ] owner info
        - [ ] add event
    - [ ] event pages
        - [ ] event info
        - [ ] pictures
        - [ ] add pictures
- [ ] login

## Functionality
- [ ] address: add/search/delete
- [ ] events: add/delete
    - event info
    - event tags
- [ ] remote upload to S3
- [ ] sync
    - [ ] sync up
    - [ ] sync down
- [ ] login

## Test on iPhone
Developing on Android but meant to be deployed on iPhone, have both platforms

## notes
- bottom navbar of event view(pictures) is probably not right based on v2
- should be able to use same Node/Express API that PWA uses