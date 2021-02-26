# GigaTECH Development Challenge

Hi! Thank you for your interest in [GigaTECH][gigatech]. Our hiring process may include a development challenge. This challenge allows us to gauge some of your basic software skill set. We will follow the challenge up with a technical interview to discuss what you have submitted.

We appreciate that any coding challenge represents an investment of your time. We hope you see the value in having a code sample that is relatable to both of us for the interview. Should you be unsuccessful, you should feel free to use the code you developed for this challenge in any way that you would like.

## The Challenge

One of the challenges we face as software developers is the ability to find and consume the appropriate information specific to a task while disregarding what does not matter at that point in time. This challenge is designed for you to consume information and write a small javascript browser based application. We will expose you to some of the technologies we deal with everyday, such as [FHIR &reg;][fhir] and [SMART &reg;][smarttech]. You are not expected to learn these technologies but merely use them to create the browser based application.

A common problem for clinicians today is how to extend their Electronic Health Record (EHR) applications with functionality that is useful. New functionality must not interfere with their current workflow. SMART &reg; offers a mechanism to do just that. We would like for you to develop a browser based application that uses the [EHR launch sequence](http://www.hl7.org/fhir/smart-app-launch/#ehr-launch-sequence) to display the allergies (in json format) for the current patient being viewed in the EHR.

Ideally, this would take a junior developer no more than 1 hour to complete.

## Minimum Requirements

    Your browser based application must meet this minimum requirements.

- The application shall run on the following host/port, http://127.0.0.1:8080/, with the "npm run serve" command.
- The application shall display the allergy information for the selected patient.
- The application shall display an error message indicating allergies were not found if no allergies were found for the selected patient.
- The application shall use any provider (clinician) available when being launched.
  - Dr. Albertine Orn is a good default provider with which to log in with
- The application shall work with any patient in the patient list.
  - Ms. Mariana Acuna has at least one allergy.

## Prerequisites

- A basic understanding of vanilla javascript
- A basic understanding of JSON

## Getting started

## Submission

When you are comfortable with your results, please email your fork to [GigaTECH Development Challenge][gthr]. Please keep your emails short and to the point.

Any specific notes or further information you would like to add about your submittal, should be included in the GitHub project, as additional [GitHub Markdown][ghmd] notes.

Do not feel as though you must create a public fork of this repository. You are free to create a throwaway GitHub account or private fork. In those cases, please let us know, at the above address, so that we may send you the GitHub IDs to add to the repository.

## Evaluations

## License

This project is [MIT Licensed](LICENSE).

## References

The following references may be useful in this challenge.

- [Github Markdown][ghmd]

[gthr]: mailto:HR@giagatech.net?subject=[GigaTECH%20Development%20Challenge]%20Submittal "GigaTECH HR email submittal"
[gigatech]: https://gigatech.net "GigaTECH Home"
[ghmd]: https://guides.github.com/features/mastering-markdown/ "Github Markdown"
[smarttech]: http://docs.smarthealthit.org/ "SMART technical reference"
[fhir]: https://hl7.org/fhir "FHIR Specification"
[homebrew]: https://brew.sh/ "MacOS Homebrew"
[nvm]: https://github.com/nvm-sh/nvm/blob/master/README.md "Node version manager"
[node]: https://nodejs.org/en/ "Node JS"
