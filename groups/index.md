```http
GET https://vrchat.com/api/1/groups/grp_09cf5947-252e-452e-b0c3-53ed19e40922?includeRoles=true&purpose=group
```


Response (if not member)

```json
{
    "badges": [],
    "bannerId": null,
    "bannerUrl": "https://assets.vrchat.com/www/groups/default_banner.png",
    "createdAt": "2023-02-04T00:07:09.865Z",
    "description": "test",
    "discriminator": "9859",
    "galleries": [{
        "createdAt": "2024-12-17T22:22:56.371Z",
        "description": "Shots of some of our Events⁄Apples performances",
        "id": "ggal_43f01345-b6bf-4bce-a390-5a272dff5114",
        "membersOnly": false,
        "name": "Shows",
        "roleIdsToAutoApprove": [],
        "roleIdsToManage": [],
        "roleIdsToSubmit": [],
        "roleIdsToView": null,
        "updatedAt": "2024-12-17T22:22:56.371Z"
    }],
    "iconId": null,
    "iconUrl": "https://assets.vrchat.com/www/groups/default_icon.png",
    "id": "grp_09cf5947-252e-452e-b0c3-53ed19e40922",
    "isVerified": false,
    "joinState": "open" | "request",
    "languages": ["eng"], // can be empty
    "links": ["https://discord.gg/DF52DXjyqv"],
    "memberCount": 29,
    "memberCountSyncedAt": "2025-06-13T05:56:33.123Z",
    "membershipStatus": "inactive" | "requested" | "member", // about ur relation to the group
    "name": "test",
    "onlineMemberCount": 0,
    "ownerId": "usr_7c941118-bd88-4476-9ba1-2fd5a5ce8809",
    "privacy": "default",
    "rules": "",
    "shortCode": "TEST",
    "storeId": "esto_75b7106f-69dd-44f4-97e5-6e5b389b1fcd",
    "tags": []
}
```


Response (if member)

```
{
    "badges": [],
    "bannerId": "file_2db74403-b3a3-4724-a43d-d2d75696e53b",
    "bannerUrl": "https://api.vrchat.cloud/api/1/file/file_2db74403-b3a3-4724-a43d-d2d75696e53b/1/file",
    "createdAt": "2022-12-03T16:20:59.605Z",
    "description": "A group for all furendsǃ",
    "discriminator": "4321",
    "galleries": [{
        "createdAt": "2022-12-06T16:15:22.811Z",
        "description": "Here where you can share photos",
        "id": "ggal_e54d41aa-acf3-43b6-8efe-50fca1db5c41",
        "membersOnly": false,
        "name": "Main Group photos",
        "roleIdsToAutoApprove": [],
        "roleIdsToManage": [],
        "roleIdsToSubmit": [],
        "roleIdsToView": null,
        "updatedAt": "2022-12-06T16:15:22.811Z"
	}],
    "iconId": "file_de709066-acda-4cb5-98ba-6f640fb4127f",
    "iconUrl": "https://api.vrchat.cloud/api/1/file/file_de709066-acda-4cb5-98ba-6f640fb4127f/1/file",
    "id": "grp_24733ed8-ebaf-4877-b670-6afae2f00ae2",
    "isVerified": false,
    "joinState": "open",
    "languages": ["spa", "eng", "hun"],
    "lastPostCreatedAt": null,
    "links": [],
    "memberCount": 4740,
    "memberCountSyncedAt": "2025-06-12T06:18:22.839Z",
    "membershipStatus": "member",
    "myMember": {
        "groupId": "grp_24733ed8-ebaf-4877-b670-6afae2f00ae2",
        "has2FA": false,
        "id": "gmem_4bad50fb-48c8-42ae-8402-26d9825bda7a",
        "isRepresenting": false,
        "isSubscribedToAnnouncements": true,
        "joinedAt": "2025-06-10T06:04:44.091Z",
        "lastPostReadAt": null,
        "mRoleIds": [],
        "membershipStatus": "member",
        "permissions": ["group-instance-join", "group-instance-open-create", "group-instance-plus-create", "group-instance-public-create", "group-members-viewall"],
        "roleIds": ["grol_0aee7c07-ddf1-4896-bc09-0f08f9fd5ed7"],
        "userId": "usr_2780213c-7d69-4974-91d5-b5617890f7d4",
        "visibility": "visible"
    },
    "name": "Furry",
    "onlineMemberCount": 268,
    "ownerId": "usr_ff388919-9361-447f-807c-756f2774cb6c",
    "privacy": "default",
    "roles": [{
        "createdAt": "2022-12-03T16:20:59.650Z",
        "description": "The owner of this group.",
        "groupId": "grp_24733ed8-ebaf-4877-b670-6afae2f00ae2",
        "id": "grol_ea9f5c67-e3d1-48bb-b729-65381651125b",
        "isAddedOnJoin": false,
        "isManagementRole": true,
        "isSelfAssignable": false,
        "name": "Group Owner",
        "order": 0,
        "permissions": ["*"],
        "requiresPurchase": false,
        "requiresTwoFactor": false
    }, {
        "createdAt": "2022-12-03T16:22:14.703Z",
        "description": "",
        "groupId": "grp_24733ed8-ebaf-4877-b670-6afae2f00ae2",
        "id": "grol_8dd3baeb-f97c-44c9-b926-6b9dc94ebceb",
        "isAddedOnJoin": false,
        "isManagementRole": true,
        "isSelfAssignable": false,
        "name": "Admin",
        "order": 1,
        "permissions": ["group-members-manage", "group-data-manage", "group-audit-view", "group-roles-manage", "group-roles-assign", "group-bans-manage", "group-members-remove", "group-members-viewall", "group-galleries-manage", "group-announcement-manage", "group-invites-manage", "group-instance-moderate", "group-instance-open-create", "group-instance-restricted-create", "group-instance-join"],
        "requiresPurchase": false,
        "requiresTwoFactor": false
    }, {
        "createdAt": "2022-12-06T16:33:41.852Z",
        "description": "",
        "groupId": "grp_24733ed8-ebaf-4877-b670-6afae2f00ae2",
        "id": "grol_934d2cad-3ae2-46df-b428-b2efa6e2bf80",
        "isAddedOnJoin": false,
        "isManagementRole": true,
        "isSelfAssignable": false,
        "name": "Friend",
        "order": 2,
        "permissions": ["group-members-viewall", "group-instance-restricted-create", "group-instance-join", "group-instance-open-create", "group-instance-moderate", "group-instance-plus-create"],
        "requiresPurchase": false,
        "requiresTwoFactor": false
    }, {
        "createdAt": "2022-12-03T16:20:59.663Z",
        "description": "A member of the group.",
        "groupId": "grp_24733ed8-ebaf-4877-b670-6afae2f00ae2",
        "id": "grol_0aee7c07-ddf1-4896-bc09-0f08f9fd5ed7",
        "isAddedOnJoin": true,
        "isManagementRole": false,
        "isSelfAssignable": false,
        "name": "Member",
        "order": 3,
        "permissions": ["group-instance-open-create", "group-instance-join", "group-members-viewall", "group-instance-plus-create", "group-instance-public-create"],
        "requiresPurchase": false,
        "requiresTwoFactor": false
    }, {
        "createdAt": "2024-03-29T10:09:18.174Z",
        "defaultRole": true,
        "description": "Permissions applied to all group members.",
        "groupId": "grp_24733ed8-ebaf-4877-b670-6afae2f00ae2",
        "id": "grol_af7a17ba-7a2b-4014-982b-715b55137c03",
        "isAddedOnJoin": false,
        "isManagementRole": false,
        "isSelfAssignable": false,
        "name": "Everyone",
        "order": 99999997,
        "permissions": [],
        "requiresPurchase": false,
        "requiresTwoFactor": false
    }],
    "rules": "Rule 1\nTreat your fellow members as equals․ Be supportive of others․ Absolutely zero harassment‚ witch hunting‚ sexism‚ racism‚ or hate speech will be tolerated․\nRule 2\nIf you see something against the rules or makes you feel unsafe‚ inform our staff․ We want this group to be a welcoming spaceǃ\nRule 3\nNo spam‚ mass-mention in our group․\nRule 4\nNo NSFW or otherwise inappropriate content in any pictures and avatarsǃ\nRule 5\nNo violent or illegal content․ This includes text‚ images‚ or links featuring gore‚ hard violence‚ suicide‚ drug use‚ or other graphically disturbing content․",
    "shortCode": "FURRY",
    "tags": []
}
```
