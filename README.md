# CC
{
	"id": "b1745e38-c3c8-479c-a038-94128f726a65",
	"name": "GiHub_Issues",
	"timestamp": "2023-09-17T17:11:59.071Z",
	"collection_id": "25495284-35e04fea-9940-40ee-aa14-7511e6b4589f",
	"folder_id": 0,
	"environment_id": "0",
	"totalPass": 6,
	"delay": 0,
	"persist": true,
	"status": "finished",
	"startedAt": "2023-09-17T17:11:54.724Z",
	"totalFail": 0,
	"results": [
		{
			"id": "6ccfa567-b7b6-48b4-9ae9-3be312e2c397",
			"name": "New Request",
			"url": "https://api.github.com/repos/kampfetka/CC/issues",
			"time": 1195,
			"responseCode": {
				"code": 201,
				"name": "Created"
			},
			"tests": {
				"Status code is 201": true
			},
			"testPassFailCounts": {
				"Status code is 201": {
					"pass": 1,
					"fail": 0
				}
			},
			"times": [
				1195
			],
			"allTests": [
				{
					"Status code is 201": true
				}
			]
		},
		{
			"id": "7583279f-0b45-4c6f-a491-faf3e89ea377",
			"name": "Get issues",
			"url": "https://api.github.com/repos/kampfetka/CC/issues",
			"time": 272,
			"responseCode": {
				"code": 200,
				"name": "OK"
			},
			"tests": {
				"Status code is 200": true
			},
			"testPassFailCounts": {
				"Status code is 200": {
					"pass": 1,
					"fail": 0
				}
			},
			"times": [
				272
			],
			"allTests": [
				{
					"Status code is 200": true
				}
			]
		},
		{
			"id": "87a1ea84-62d4-4d07-803d-2e48310c4024",
			"name": "Update an issue",
			"url": "https://api.github.com/repos/kampfetka/CC/issues/17",
			"time": 562,
			"responseCode": {
				"code": 200,
				"name": "OK"
			},
			"tests": {
				"Status code is 200": true
			},
			"testPassFailCounts": {
				"Status code is 200": {
					"pass": 1,
					"fail": 0
				}
			},
			"times": [
				562
			],
			"allTests": [
				{
					"Status code is 200": true
				}
			]
		},
		{
			"id": "e7f42616-32de-46fc-aa7b-42934285c1f0",
			"name": "Get an issue",
			"url": "https://api.github.com/repos/kampfetka/CC/issues/17",
			"time": 284,
			"responseCode": {
				"code": 200,
				"name": "OK"
			},
			"tests": {
				"Status code is 200": true
			},
			"testPassFailCounts": {
				"Status code is 200": {
					"pass": 1,
					"fail": 0
				}
			},
			"times": [
				284
			],
			"allTests": [
				{
					"Status code is 200": true
				}
			]
		},
		{
			"id": "b14b38b3-6fa5-4361-83bc-f67ca4c1a5e9",
			"name": "Lock an issue",
			"url": "https://api.github.com/repos/kampfetka/CC/issues/17/lock",
			"time": 485,
			"responseCode": {
				"code": 204,
				"name": "No Content"
			},
			"tests": {
				"Status code is 204": true
			},
			"testPassFailCounts": {
				"Status code is 204": {
					"pass": 1,
					"fail": 0
				}
			},
			"times": [
				485
			],
			"allTests": [
				{
					"Status code is 204": true
				}
			]
		},
		{
			"id": "003893f3-45a3-4452-a117-d25b87548cea",
			"name": "Get a locked issue",
			"url": "https://api.github.com/repos/kampfetka/CC/issues/17",
			"time": 377,
			"responseCode": {
				"code": 200,
				"name": "OK"
			},
			"tests": {
				"Status code is 200": true
			},
			"testPassFailCounts": {
				"Status code is 200": {
					"pass": 1,
					"fail": 0
				}
			},
			"times": [
				377
			],
			"allTests": [
				{
					"Status code is 200": true
				}
			]
		}
	],
	"count": 1,
	"totalTime": 3175,
	"collection": {
		"requests": [
			{
				"id": "6ccfa567-b7b6-48b4-9ae9-3be312e2c397",
				"method": "POST"
			},
			{
				"id": "7583279f-0b45-4c6f-a491-faf3e89ea377",
				"method": "GET"
			},
			{
				"id": "87a1ea84-62d4-4d07-803d-2e48310c4024",
				"method": "PATCH"
			},
			{
				"id": "e7f42616-32de-46fc-aa7b-42934285c1f0",
				"method": "GET"
			},
			{
				"id": "b14b38b3-6fa5-4361-83bc-f67ca4c1a5e9",
				"method": "PUT"
			},
			{
				"id": "003893f3-45a3-4452-a117-d25b87548cea",
				"method": "GET"
			}
		]
	}
}
