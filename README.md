# Interactive Tasks in Union

Interactive Tasks streamline the AI workflow development process by enabling secure, interactive debugging of remote executions directly from a VS Code IDE or Jupyter notebook. This feature, originally contributed by LinkedIn Engineering as FlyteInteractive, has been fully integrated into Union, enhancing development velocity and bridging the gap between local and remote execution environments.

## Key Features

- **Local-Remote Execution Parity**: Union minimizes the disparity between local and remote executions through features like ImageSpec, local execution capabilities, and Agents, facilitating a seamless development experience.
- **Interactive Debugging**: With the `@vscode` decorator, developers can attach a VS Code IDE to any running remote execution, allowing for real-time code editing, breakpoint setting, and line-by-line debugging in near-production environments.
- **Development Efficiency**: Interactive Tasks dramatically reduce the cycle time for developing, testing, and deploying AI workflows by enabling direct interaction with remote executions, thus accelerating the path to production.

## Example Usage

The example provided demonstrates how to use Interactive Tasks for developing AI workflows with Union. It illustrates the process from defining dependencies and workflows in code to debugging remote executions interactively.

## Conclusion

Union's Interactive Tasks feature represents a significant leap forward in AI workflow development, offering developers an efficient and integrated tool for debugging and optimizing AI models at scale. For more information, visit [Union](https://www.union.ai/).

Credits to LinkedIn Engineering for their foundational contribution of FlyteInteractive, which plays a pivotal role in enhancing the capabilities of the Flyte open-source project.

---

For a demo and additional resources:
- [LinkedIn team demo of FlyteInteractive](https://youtu.be/YFaM-y8UWIo?feature=shared&t=3768)
- [LinkedIn example repository for FlyteInteractive](https://github.com/troychiu/flyteinteractive_demo/tree/main)
- [FlyteInteractive documentation](https://docs.flyte.org/en/latest/flytesnacks/examples/flyin_plugin/index.html)
