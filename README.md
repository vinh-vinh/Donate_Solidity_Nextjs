    // let addresses, addressCount;
    // try {
    //   addressesCount = await ContractName.methods.getCampaignCounts().call();

    //   addresses = await Promise.all(
    //     Array(parseInt(addressesCount))
    //       .fill()
    //       .map((element, index) => {
    //         return ContractName.methods.getAddressByIndex(index).call();
    //       })
    //   );
    // } catch (e) {
    //   console.log("error in pulling array list", e);
    // }