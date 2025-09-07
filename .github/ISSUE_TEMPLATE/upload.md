---
name: File Upload
description: ファイルをアップロードします
title: "Upload: [ファイル名]"
labels: ["upload"]
assignees: []
body:
  - type: textarea
    id: file_data
    attributes:
      label: ファイルデータ（Base64）
      description: アップロードするファイルのBase64エンコードデータを貼り付けてください
      placeholder: data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAA...
    validations:
      required: true
  - type: textarea
    id: file_name
    attributes:
      label: ファイル名
      description: ファイル名を入力してください（拡張子を含む）
      placeholder: example.png
    validations:
      required: true
