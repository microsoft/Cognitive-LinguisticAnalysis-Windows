# Microsoft Linguistic Analysis API: Windows Client Library & Sample
This repo contains the Windows client library & sample for the Microsoft Linguistic Analysis API, an offering within [Microsoft Cognitive Services](https://www.microsoft.com/cognitive-services), formerly known as Project Oxford.

* [Learn about the Linguistic Analysis API](https://www.microsoft.com/cognitive-services/en-us/linguistic-analysis-api)
* [Read the documentation](https://www.microsoft.com/cognitive-services/en-us/linguistic-analysis-api/documentation/overview)
* [Find more SDKs & Samples](https://www.microsoft.com/cognitive-services/en-us/SDK-Sample?api=linguistic%20analysis)

## Getting Started
To obtain a subscription key for Linguistic Analysis, [visit our website](<https://www.microsoft.com/cognitive-services/en-us/sign-up>) and sign up for free using a Microsoft account.
Then open, modify, build, and run the accompanying Visual Studio solution.
This sample is a C# Windows console application demonstrating the use of the Microsoft Linguistic Analysis API.

### Build the Sample
 1. Start Microsoft Visual Studio 2015 and select File &gt; Open &gt; Project/Solution.
 2. Starting in the folder where you clone the repository, go to the LinguisticAnalysis &gt; Windows &gt; Sample folder.
 3. Double-click the Visual Studio 2015 Solution file .sln.
 4. Paste your Microsoft Cognitive Services Linguistic Analysis subscription key into the LinguisticsClient constructor parameter value in Program.cs.
 5. Press Ctrl+Shift+B, or select Build &gt; Build Solution.

### Run the Sample
After the build is complete, press F5 to run the sample.

A number of lines will be printed on the console, showing the results received from the Linguistics service.
These include: listing the set of available analyzers, and printing the results of those analyzers on some simple text.

Press any key to exit the app.


## Contributing
We welcome contributions. Feel free to file issues and pull requests on the repo and we'll address them as we can. Learn more about how you can help on our [Contribution Rules & Guidelines](</CONTRIBUTING.md>). 

You can reach out to us anytime with questions and suggestions using our communities below:
 - **Support questions:** [StackOverflow](<https://stackoverflow.com/questions/tagged/microsoft-cognitive>)
 - **Feedback & feature requests:** [Cognitive Services UserVoice Forum](<https://cognitive.uservoice.com>)

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.


## License
All Microsoft Cognitive Services SDKs and samples are licensed with the MIT License. For more details, see
[LICENSE](</LICENSE.md>).

Sample images are licensed separately, please refer to [LICENSE-IMAGE](</LICENSE-IMAGE.md>)

## Developer Code of Conduct
Developers using Cognitive Services, including this client library & sample, are expected to follow the “Developer Code of Conduct for Microsoft Cognitive Services”, found at [http://go.microsoft.com/fwlink/?LinkId=698895](http://go.microsoft.com/fwlink/?LinkId=698895).
