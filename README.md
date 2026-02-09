### 🚀 Project: Mastering Go (Golang)

#### 🎯 1. Title & Objective

**Technology Chosen**: Go (Golang)
**The "Why"**: I chose Go for its incredible efficiency, native support for concurrency since we'll be scraping multiple websites, lightning-fast cloud-native applications since the app has to be online in intervals.
**End Goal:** To build robust, scalable app that demonstrates Go's simplicity and performance.

#### 📖 2. Quick Summary of the Technology

**What is it ?** Go is an open-source programming language developed by Google. It is staticallly typed, compiled
and designed for simplicity and reliability.
**Where is it used?** It's the backbone of modern cloud infrastructure, microservices and DevOpts tools.
**Real-World Example:** **Docker** and **Kubernetes** are both build almost entirely in Go

#### 🖥️ 3. System Requirements

To run this project you'll need:

- **OS**: Windows 10+, MacOS, Linux
- **Tools**: [Go Compiler](https://go.dev/dl) (V1.25+ recommended)
- **Editor**: VS Code (with the Go extension) or GoLand
- **Terminal**: Gib Bash, Zsh, PowerShell

#### 🛠️ 4. Installation & Setup Instructions

**1. Download Go:** Visit the [official download page] and install the package for your OS.

**2. Verify Installation:**

```shell
go version
```

**3. Initialize the Project**

```shell
mkdir price-estimate && price-estimate
go mod init github.com/japheth-waswa/price-estimate
```

**4. Install Dependencies (if any):**

```shell
go mod tidy
```

### ⚡️ 5. Minimal Working Example

`main.go`

```shell
package main

import "fmt"

func main() {
    message := "Hello world"
    fmt.Println(message)
}
```

**How to run:**

```shell
go run main.go
```

**Expected Output:**
`Hello World`

**Explanation:** This code declares a main package, imports the `fmt` (format) library and uses the
`Println` function to output a string to the console

### 🤖 6. AI Prompt Journal

> **Note:** This section documents my collaboration with AI to solve specific hurdles during the development of this Go project.

| Date | AI Prompt (What I Asked) | AI Response Summary | Evaluation & Impact | :--- | :---
