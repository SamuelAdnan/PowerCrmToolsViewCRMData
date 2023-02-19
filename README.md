# PowerCrmToolsViewCRMData
A devops task utility to create simple fetchxml and view crm data. It also contains task which reads fetchxml from one crm and upsert data in other crm.

# Compatibility
Dynamics365 9
Customer engagement online versions
Hosted Azure Agents

# Parameters
OAUth source Crm connection string
Fetchxml
Record count (paging large record sets)
Export as CSV / JSON
OAUth destinationCrm connection string
PAT and Service connection name.

# Tasks

## Service connection (required for Task1 an Tash 2 but optional for task 3)
![Service connectiont](https://github.com/SamuelAdnan/PowerCrmToolsViewCRMData/blob/main/images/conimage.png?raw=true)
Task 2 can only be used if we define the service connection and run the task 2
# Video
[![SC2 Video](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/videolinkfile2.png?raw=true)](https://youtu.be/kDt3lm388UY)

## 1 Interactive-WebAPI (selection based)
[Power Crm Tools WebAPI Installer Upsert Data](https://github.com/SamuelAdnan/PowerCrmToolsViewCRMData/blob/main/images/task1.png?raw=true). A task needed to setup dataverse interactive webapi. Must be initialize first.<br />


## 2 PowerCRMFetchxmlUpsertData
[PowerCRMFetchxmlUpsertData](https://github.com/SamuelAdnan/PowerCrmToolsViewCRMData/blob/main/images/task2.png?raw=true). Power Crm WebAPI. An interactive tool to build simple fetchxml and view crm data.<br />

## 3 [Power Crm fetchxml builder
[Power Crm fetchxml builder](https://github.com/SamuelAdnan/PowerCrmToolsViewCRMData/blob/main/images/task3.png?raw=true). Power Crm tools to read simple fetchxml and upsert to destination crm.<br />


# Issues
For issues (https://github.com/SamuelAdnan/PowerCrmToolsViewCRMData/issues).


# LinkedIn
[Adnan Samuel](https://www.linkedin.com/in/adnan-samuel-16659418/)

# EULA
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
